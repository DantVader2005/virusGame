# virusGame
a game about a atventure inside your body je wil play as a bleu cell and your missione is dont let the red cells reschars your heart!

float redCellX0 = 1375;
float redCellX1 = 1975;
float redCellX2 = 2875;
float levensStrook = 100;
float aantalVirussen = 1;
float rechtsen[] = new float[100];
boolean is_poppetje_dood = false;
PImage zwaard;
PImage titelScherm;
PImage shield;
void setup(){
  shield = loadImage("shield-02[1].png");
  zwaard= loadImage("sword_PNG5525[1].png");
  titelScherm= loadImage("titelScherm.png");
  size(1375,800);
  background(237,98,110);
  fill(237,43,59);
  rect(0,400,1375,400);
  fill(0,0,200);
  for (int i=0; i<100; i+=1) { rechtsen[i] = i; }
}

void draw(){
  /*
  background(237,98,110);
 fill(237,43,59);
rect(0,400,1375,400);
if (is_poppetje_dood == true){
  aantalVirussen=aantalVirussen + 1;
  is_poppetje_dood=false;
  redCellX0=1375;
  redCellX1= 1375;
  redCellX2= 1375;
  levensStrook = 100;
}
if (is_poppetje_dood == false) 
{
  redCellX0 = redCellX0-3;
   redCellX1 = redCellX1-3;
    redCellX2 = redCellX2-3;
  fill(255,0,0);
  ellipse (redCellX0,400,100,100) ;
  ellipse (redCellX1,400,100,100) ;
  ellipse (redCellX2,400,100,100) ;
}
fill(0,0,200);
ellipse(pmouseX,pmouseY,100,100);
 image (shield,pmouseX,pmouseY-20,60,60);
  image(zwaard,pmouseX,pmouseY-20,80,60);
  fill(0,255,0);
  rect (redCellX0,300,levensStrook,2);
  rect (redCellX1,300,levensStrook,2);
  rect (redCellX2,300,levensStrook,2);
  if(dist(pmouseX,pmouseY,redCellX0,400)<= 100) { levensStrook  = levensStrook-1; }
  if(dist(pmouseX,pmouseY,redCellX1,400)<= 100) { levensStrook  = levensStrook-1; }
  if(dist(pmouseX,pmouseY,redCellX2,400)<= 100) { levensStrook  = levensStrook-1; }
  if(levensStrook<=0) 
  { 
    levensStrook=0;
    is_poppetje_dood = true;
  }
  fill(95,1,1);

  for (int i=0; i<100; i+=1)
  {
    fill(255,0,0);
             ellipse(rechtsen[i],100,100,100);
  }
  */
  image(titelScherm,1375,800);
}
like you the code folow me to more codes! #tis is make in prosecing
