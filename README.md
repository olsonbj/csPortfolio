# csPortfolio

* WebPage [here]()
* Lightning Java [here](https://olsonbj.github.io/lightning2/)
* Lightning JS [here]()
* Dice [here] ()

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
