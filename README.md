# Ben Olson's ACS Portfolio!!!!!!!
### WOWWIE!

Lab! | Link!
---|---
 Webpage | [open here!](https://github.com/olsonbj/Bet/blob/gh-pages/website/bet.html)
 Lightning | [open here!](
 Dice | [open here!](
 Starfield | [open here!](
 St. Olaf College Presentation | [open here!](

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
