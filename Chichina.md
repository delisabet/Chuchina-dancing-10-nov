Chuchina-dancing-10-nov
=======================

//Skirt color change and mouse pressed
int x; 
int y;
int value = 0;
  
void setup() {
  size(640, 360);
  stroke(255);
  frameRate(30);
 x=150;
  y=160; 
  background(0);
  float rand = 0;
 
  }

void draw() {  
  background (value );  
  noStroke ();
  fill(#FFE47B);
  //ellipse ( x, y, Width, Height)//
  ellipse( x, y, 110, 95 ); 
  //hat//

  noStroke ();
  fill(#000000);
  ellipse( x, 170, 70, 60 ); 
  //hair//

  noStroke ();
  fill(#E8AF82);
  ellipse( x+25, 350, 20, 25 ); 
  //right foot//

  noStroke ();
  fill(#E8AF82);
  ellipse( x-20, 350, 20, 25 ); 
  //left foot//


  noStroke ();
  //FF434B
  fill(random(200), 67, 75);
  arc(x, 200, 300, 300, radians(35), radians(145)); 
  //arc(x,y, witdth, height, start, stop)//
  // start  = 3 o'cloock =0 )//
  //stop 0 PI.0.5= un quarto  pero PI= semicirculo) //
  // RED SKIRT//

  noStroke ();
  fill(255, random(200), 100);
  arc(x, 200, 260, 260, radians(35), radians(145)); 
  //arc(x,y, witdth, height, start, stop)//
  // blue skirt//

  noStroke ();
  fill(255, 228, random(200));
  arc(x, 200, 210, 210, radians(35), radians(145)); 
  //arc(x,y, witdth, height, start, stop)//
  // YELLOW SKIRT//

  noStroke ();
  fill(#E8AF82);
  ellipse( x+97, 206, 20, 15 ); 
  //manita derecha- right hand//

  noStroke ();
  fill(#E8AF82);
  ellipse( x-96, 206, 20, 15 ); 
  //manita izquierda- left hand //

  noStroke ();
  fill(#FFE47B);
  rect(x-93, 198, 185, 16); 
  //brazos//

  noStroke ();
  fill(#ffffff);
  arc(x, 190, 150, 140, 0, PI); 
  //arc(x,y, witdth, height, start, stop)//
  // start  = 3 o'cloock =0 )//
  //stop 0 PI.0.5= un quarto  pero PI= semicirculo) 
  //camisa//

  //-------------braid-----------------//
  noStroke ();
  fill(#000000);
  ellipse( x+27, 189, 12, 12 ); 
  //trenza1//
  noStroke ();
  fill(#000000);
  ellipse( x+29, 197, 10, 8 ); 
  //trenza2//
  noStroke ();
  fill(#000000);
  ellipse( x+28, 204, 10, 8 ); 
  //trenza3//
  noStroke ();
  fill(#000000);
  ellipse( x+27, 210, 10, 8 ); 
  //trenza4//
  noStroke ();
  fill(#000000);
  ellipse( x+26, 217, 10, 8 ); 
  //trenza5//
  noStroke ();
  fill(#000000);
  ellipse( x+27, 224, 10, 8 ); 
  //trenza 6//
  noStroke ();
  fill(#000000);
  ellipse( x+28, 230, 10, 8 ); 
  //trenza7//
  noStroke ();
  fill(#000000);
  ellipse( x+29, 237, 10, 8 ); 
  //trenza8//
  //-----------------------braid----------------------//

  //noStroke ();
  fill(#E8AF82);
  ellipse( x, 200, 16, 10 ); 
  //cuellito//

  noStroke ();
  fill(#E8AF82);
  ellipse( x, 176, 60, 50 ); 
  //cabeza//

  noStroke (); 
  fill(#FF434B);
  arc(x, 190, 12, 9, 0, PI); 
  //arc(x,y, witdth, height, start, stop)//
  // start  = 3 o'cloock =0 )//
  //stop 0 PI.0.5= un quarto  pero PI= semicirculo) 
  //boquita//

  noStroke ();
  fill(#000000);
  ellipse( x-12, 172, 7, 6 ); 
  //ojo izquierdo////

  noStroke ();
  fill(#000000);
  ellipse( x+16, 172, 7, 6 ); 
  //ojo derecho////

if ( x<490) {x= x+1;  
 }
}
void mousePressed() {
  if (value == 0) {
    value = #66CDAA ;
  } else {
    value = 0;
  }
}
