# Junior Front-End Developer

## 1. Name

### Egor Nedelko 

___

## 2. Contact Info
Email: gojiramedia@gmail.com Telegram: @egornedelko

---
## 3. Summary 

I'm an aspiring web developer who's very much interested in computer science in general. My current goal is to become a well-rounded specialist in the front-end field. Once I'm there and gained enough experience, perhaps full-stack is going to be the next landmark for me. I'm fond of learning new things, challenging tech inspires me. 

---  

## 4. Skills  

* HTML, CSS, JS, Git
* OOP (Java)
* БЭМ
* Photoshop, Illustrator, Figma
* Visual Studio Code

---  

## 5. Code example  

```javascript

window.onload=function() {
canv=document.getElementById("gc");
ctx=canv.getContext("2d");
document.addEventListener("keydown", keyPush);
setInterval(game, 1000/15);

for (var i=0;i<trail.length;i++) {
    ctx.fillRect(trail[i].x*gs, trail[i].y*gs, gs-2, gs-2);
    if(trail[i].x==px && trail[i].y==py) {
        tail = 5;
    }
}

trail.push({x:px,y:py});
   while(trail.length > tail) {
     trail.shift();       
   }
}

```

---  
## 6. Experience 
No commercial projects so far. As part of self-education, I wrote a console version of Checkers in Java, which helped me immensely to practice the basics of OOP. Here's a code example from that project :  
```java

public void calculate_bivector_queen_direction (String queenLoc, String extraLoc) {
    ArrayList<String> path1 = new ArrayList<String> ();
    ArrayList<String> path2 = new ArrayList<String> ();

    for (ArrayList<String> dir : tool.directions) {
        if ((dir.contains(queenLoc)) && (dir.contains(extraLoc))) {
            float queenIndex = (float) dir.indexOf(queenLoc);

            for (float i = queenIndex + 1; i < dir.size (); i++) {
                path1.add (dir.get ( (int) i));
            } 
            tool.queenFronts.add (path1);
            
            for (float i = queenIndex - 1; i >= 0; i--) {
                path2.add (dir.get ( (int) i));
            }   
            tool.queenFronts.add (path2);
        }
    }
}

```   
---

## 7. Education 
* 2012 - 2017 | Minsk State Linguistic University
* Self-education | HTML Academy, Code-basics, workshops and tutorials

---

## 8. English Level
B2+ High intermediate 
