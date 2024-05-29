# 10.1-Rainbow-Line

```
let lineY = 50;

function setup() {
    createCanvas(600, 600);
    background(255, 255,0);
}// end of setup

function draw() {
  line(50, lineY, mouseX,mouseY);
  lineY = lineY + 2;

  
}//end draw

function mousePressed(){
  background(255, 255,0);
}// end of mouse pressed
```
