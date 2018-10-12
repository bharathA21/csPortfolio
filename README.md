# csPortfolio

* [Web Page!](https://bharatha21.github.io/WebPageAashish/WebTest/Vacations.html)
* Ligntning [here] (https://bharatha21.github.io/lightning2/)
* [Dice](https://bharatha21.github.io/dice3/)
* [Chemotaxis] (https://bharatha21.github.io/chemotaxis4/) 

* tough code (code that's difficult)

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
