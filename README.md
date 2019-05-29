# Ben Olson's ACS Portfolio!!!!!!!
### *OVERVIEW WOWWWWW!!!!!!*
##### This wepbage is designed to showcase my code from Advanced Computer Science run by Dr. R. Projects include a webpage, lightning, dice, chemotaxis, starfield, a college presentation, and other projects!

Project! | WEBPAGE!
---|---
 Webpage | [CLICK TO VIEW!](https://olsonbj.github.io/Bet/)
 Lightning | [CLICK TO VIEW!](https://raw.githubusercontent.com/ACS-2018-2019/Olson.B/master/projectpics/lightningpic.png?token=AHSL5QYURNXSAMA6FTYVLBC464534)
 Dice | [CLICK TO VIEW!](https://raw.githubusercontent.com/ACS-2018-2019/Olson.B/master/projectpics/dicepic.png?token=AHSL5Q3KSSTNGWJJZDJUNXK46452Y)
 Chemotaxis (Java Script - Beta/Broken) | [CLICK TO VIEW!](https://raw.githubusercontent.com/ACS-2018-2019/Olson.B/master/projectpics/chemopic.png?token=AHSL5QZULCEWWKIRDJQZ3KK4645JK)
 Starfield | [CLICK TO VIEW!](https://olsonbj.github.io/starfield5/)
 St. Olaf College Presentation | [CLICK TO VIEW!](https://docs.google.com/presentation/d/11Z_HYkniHpBh6d3EJUPXrt_Q0RzkkVbHX8872wpqX_M/edit#slide=id.p)
 Holiday Card | [CLICK TO VIEW!](https://raw.githubusercontent.com/ACS-2018-2019/Olson.B/master/projectpics/holidaycardpic.png?token=AHSL5Q4FPN5L5OHZRPHMFHS46455O)
 Data Project | [CLICK TO VIEW!](<img src="https://raw.githubusercontent.com/ACS-2018-2019/Olson.B/master/projectpics/dataprojpic.png?token=AHSL5Q6LMHN73LQD5TSI5J24645YU">)
 Music Finder Game | [CLICK TO VIEW!]() 


### *HARD CODE! WOWWWWWW!*
##### Chemotaxis processing sound file import!
```Java
import processing.sound.*;
Note1 []a=new Note1[4];
SoundFile []allFiles=new SoundFile[4];

void setup() {
  size(600, 600);
  allFiles[0] = new SoundFile(this, "c4.wav");
  allFiles[1] = new SoundFile(this, "e4.wav");
  allFiles[2] = new SoundFile(this, "g4.wav");
  allFiles[3] = new SoundFile(this, "c5.wav");
  for (int i=0; i<a.length; i++) {
    a[i]=new Note1(width/2, height/2, 10);
  }
}

void mousePressed() {
  int num=(int)(Math.random()*4);
  println(num);
  for (int i=0; i<a.length; i++) {
    if (mouseX>a[i].getX()-a[i].getR()&&mouseX<a[i].getX()+a[i].getR()&&mouseY<a[i].getY()+a[i].getR()&&mouseY>a[i].getY()-a[i].getR()) {
      allFiles[i].play();
    }
  }
}
```
##### This code was difficult to write because I had to learn how to import sound files from the desktop to play in my project and I had never done that before. I was able to use the functionality of processing with "import processing.sound.*;" in the code. I then made it so when the mouse is clicked within the particle's perimeter, it will play one of the four sound files I imported. With the help of others and through research of the processing api, I was able to get a beta version of chemotaxis working.
