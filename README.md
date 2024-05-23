variavel da bolinha
let xbolinha = 50;  
let ybolinha = 50;
let diametro = 25;
let raio = diametro 2;

variaveis do oponente
let xraquete0oponente = 585;
let yraquete0oponente = 150;

 velocidade da bolinha
 let velocidadeXBolinha = 6;
 let velocidadeYBolinha = 6;

variaveis da raquete
let xraquete = 5;
let yraquete = 150;
let raqueteComprimento = 10;
let raqueteAltura = 90;

placar do jogo
let meuspontos = 0;
let pontosDo0ponente = 0;


sons do jogo
let raquetada;
let ponto;
let trilha;

let colidiu = false;

function setup() {
   createcanvas (600, 400)
   trilha.lop();
  
  
  function draw() {
   backgroud (0)
   mostrabolinha();
   movimentabolinha();
   verificacolisaobolinha();
    mostraraquete(xRaquete yRaquete);
    movimentaminharaquete();
    
  
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    


    
    
raquete.play();
  }
}

function verificacolisaoraquelt (x,y)
colidiu=colliderectcircle(x,y,raquetecomprimento,raqueteactionxbolinha,ybolinha)
if (colidiu) {
velocidadexbolinha*=-1
  raquete.play()
}
}

function movimentaraqueteoponente(){
 if (reytsdown(87){
yraqueteoponente-=10;
     }
 if (reyisdown(83)){
   yraqueteoponente =10;
 }
}


incluiplacar(){
  store(255)
  textalign(center)
  textsize(16)
  fill(color(255,140,0))
  rect(150,10,40,20);
  fill(255);
  text(meuspontos170,26)
  fill(color(255,140,0));
rect(450,10,40,20);
  fifill(255);
  text(pontosdooponente,470,26);
  
  
  
}
}

function marcaponto(){
  if (xbolinhas590){
    meuspontos += 1;
    ponto.play();
  }
  if(xbolinha 10){
    pontosdooponente +=1;
    ponto.play();
  }
}


functionpreload (){
  trilha=loadsound( trilha.mp3);
  ponto=loadsound
 raquete+loadsound(raquete.mp3)
  
  
  
