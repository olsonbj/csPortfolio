# Ben Olson's ACS Portfolio!!!!!!!
### WOWWIE!

Lab! | Link!
---|---
 Webpage | [CODE!](https://olsonbj.github.io/Bet/)
 Lightning | [CODE!](https://olsonbj.github.io/lightning2/)
 Dice | [CODE!](https://olsonbj.github.io/dice3/)
 Starfield | [CODE!](https://olsonbj.github.io/starfield5/)
 St. Olaf College Presentation | [CODE!](https://docs.google.com/presentation/d/11Z_HYkniHpBh6d3EJUPXrt_Q0RzkkVbHX8872wpqX_M/edit#slide=id.p)

```Java
void draw(){
  fill(0,8);
  rect(0,0,width,height);
  while(y<1000){
     endX = x + int(random(-4,4));
     endY = y + 1;
     strokeWeight(40);
     stroke((int)(Math.random()*256)+1,(int)(Math.random()*256)+1,(int)(Math.random()*256)+1);
     line(x,y,endX,endY);
     x = endX;  
     y = endY;
  }
}
```
