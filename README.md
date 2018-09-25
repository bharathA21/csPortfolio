# csPortfolio

* Web Page! [here]()
* Ligntning! [here] ()
tough code
```Java

void draw()
{
  background(85, 156, 198);

  while (endX<600) {
    stroke((int)(Math.random()*255)+1, (int)(Math.random()*255)+1, (int)(Math.random()*255)+1) ;
    endX=startX+((int)(Math.random()*10));
    endY=startY+((int)(Math.random()*19)-9);
    line(endX, endY, startX, startY);
    startX=endX;
    startY=endY;
  }
}
```
