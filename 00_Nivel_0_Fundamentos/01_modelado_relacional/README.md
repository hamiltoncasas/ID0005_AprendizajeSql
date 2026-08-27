<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Juego 2D - JavaScript</title>

<style>
body{
    margin:0;
    background:#222;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    overflow:hidden;
    font-family:Arial;
}

canvas{
    background:#87CEEB;
    border:4px solid #000;
}
</style>
</head>
<body>

<canvas id="game" width="900" height="500"></canvas>

<script>

const canvas = document.getElementById("game");
const ctx = canvas.getContext("2d");

const gravedad = 0.6;

const jugador = {
    x:100,
    y:100,
    ancho:40,
    alto:40,
    color:"red",
    vx:0,
    vy:0,
    velocidad:5,
    salto:13,
    enSuelo:false
};

const teclas = {};

document.addEventListener("keydown",(e)=>{
    teclas[e.key]=true;
});

document.addEventListener("keyup",(e)=>{
    teclas[e.key]=false;
});

function actualizar(){

    jugador.vx=0;

    if(teclas["ArrowLeft"] || teclas["a"])
        jugador.vx=-jugador.velocidad;

    if(teclas["ArrowRight"] || teclas["d"])
        jugador.vx=jugador.velocidad;

    if((teclas[" "] || teclas["ArrowUp"] || teclas["w"]) && jugador.enSuelo){
        jugador.vy=-jugador.salto;
        jugador.enSuelo=false;
    }

    jugador.vy+=gravedad;

    jugador.x+=jugador.vx;
    jugador.y+=jugador.vy;

    // Suelo
    const suelo = canvas.height-60;

    if(jugador.y+jugador.alto>=suelo){
        jugador.y=suelo-jugador.alto;
        jugador.vy=0;
        jugador.enSuelo=true;
    }

    // Límites
    if(jugador.x<0) jugador.x=0;
    if(jugador.x+jugador.ancho>canvas.width)
        jugador.x=canvas.width-jugador.ancho;
}

function dibujar(){

    ctx.clearRect(0,0,canvas.width,canvas.height);

    // Cielo
    ctx.fillStyle="#87CEEB";
    ctx.fillRect(0,0,canvas.width,canvas.height);

    // Suelo
    ctx.fillStyle="#2E8B57";
    ctx.fillRect(0,canvas.height-60,canvas.width,60);

    // Sol
    ctx.fillStyle="yellow";
    ctx.beginPath();
    ctx.arc(80,80,40,0,Math.PI*2);
    ctx.fill();

    // Jugador
    ctx.fillStyle=jugador.color;
    ctx.fillRect(jugador.x,jugador.y,jugador.ancho,jugador.alto);

    // Texto
    ctx.fillStyle="black";
    ctx.font="20px Arial";
    ctx.fillText("A/D o ← → para mover",20,30);
    ctx.fillText("ESPACIO para saltar",20,55);
}

function gameLoop(){

    actualizar();
    dibujar();

    requestAnimationFrame(gameLoop);
}

gameLoop();

</script>

</body>
</html>
