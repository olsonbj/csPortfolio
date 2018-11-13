# csPortfolio

* WebPage [here](https://olsonbj.github.io/Bet/website/bet.html)
* Lightning Java [here](https://olsonbj.github.io/lightning2/)
* Lightning JS [here]()
* Dice [here](https://olsonbj.github.io/dice3/)
* Chemotaxis [here](https://github.com/olsonbj/chemotaxis4/blob/gh-pages/Chemotaxis.pde)

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
