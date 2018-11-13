# Ben's csPortfolio

* WebPage [here](https://olsonbj.github.io/Bet/website/bet.html)
* Lightning Java [here](https://olsonbj.github.io/lightning2/)
* Lightning JS [here]()
* Dice [here](https://olsonbj.github.io/dice3/)
* St. Olaf [here](https://docs.google.com/presentation/d/11Z_HYkniHpBh6d3EJUPXrt_Q0RzkkVbHX8872wpqX_M/edit?usp=sharing)
* Chemotaxis [here](https://github.com/olsonbj/chemotaxis4/blob/gh-pages/Chemotaxis.pde)
* Starfield [here](https://olsonbj.github.io/starfield5/)

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
