# *AA Portfolio* 2018-2019

<details>
 <summary>Webpage</summary>
 <p>
  
  <a href="https://bharatha21.github.io/WebPageAashish/WebTest/Vacations.html">Web Page<br></a>
   
 
 <p>
 When I look back on my WebPage, it is really cool to see how I was able to display my cool photos from all 
        the vacations I have been on, on to a web page. This was a big step for my understanding on how much I can 
        do with java and html. It also made me realize how much I am capable of doing much more.
</p>
  </details>
   </p>
    
 
  
  
  
  
  
    <details>
 <summary>Lightning</summary>
 <p>
  
  <a href="https://bharatha21.github.io/lightning2/">Lightning<br></a>
   </p>
 
 <p>
Looking back on my Lightnig project, I remember how difficult it was to actually get the Lightning to appear
        on the screen. It was during this project that I became really comfortable asking for help when I was on the
        struggle bus. The project itself turned out good, although I might have to recheck my color schemes.
</p>
    </details>
    
    <details>
 <summary>Dice</summary>
 <p>
  
  <a href="https://bharatha21.github.io/dice3/">Dice<br></a>
   </p>
 
 <p>
Dice was one of my favorite projects we did all Tri, not only did I have fun while doing it but I figured it 
        out early and was able to tinker and make it better.
</p>
    </details>
      
    

      <details>
 <summary>Chemotaxis</summary>
 <p>
  
  <a href="https://bharatha21.github.io/chemotaxis4/">Chemotaxis<br></a>
   <a href="https://bharatha21.github.io/PracticeChemo/">Modern Art<br></a>
   </p>
 
 <p>
 Chemotaxis was rough. It was really funny how I got my project, at first I created a bunch of circle objects
 and played around with the randomizer(which crated Modern Art) and then I just messed around with it more to get my final result. I can   still make it better, but I like where I ended.  
</p>
 
    </details>

 <summary>College Presentation</summary>
 <p>
  
  <a href="https://docs.google.com/presentation/d/1dwFqulrfwr6D_06PPsU23uqHluj66n033EemwrsieE0/edit?usp=sharing">Purdue Pete<br></a>
   </p>
 
 <p>
 Chemotaxis was rough. It was really funny how I got my project, at first I created a bunch of circle objects
        and played around with the randomizer. I can still make it better, but I like where I ended.  
</p>
    </details>

  <summary>College Presentation</summary>
 <p>
  
  <a href="https://bharatha21.github.io/starfield5/">Starfield<br></a>
  
 
 <p>
 Starfield was really fun, although it was difficult and confusing, I still had a good time doing it. I ended up doing an American themed project. The most difficult part was getting the ineritance and interface to work.  
</p>
    </details>





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
