# DiamondScript Programming Language
"Built from the ground to be high-level general purpose understandnable readable easiest powerful language".
 
NOTE: DiamondScript is being built to be used, It IS NOT A REAL LANGUAGE
It's goal is to be completed even tho, in the future more things will be added. It's under contruction, but some of the codes are build and made.

# About
DiamondScript is a brand new programming language, it will be high-level powerful language and its general purpose, which means it can be used to make anything. Right now, I am testing to see what it can be use for, more code is being made. DiamondScript is not a real language, is it being build. Although, you can use it. It can be use to make game and probably to hack.

# Example
Here is an example program of who you could make a ping pong for single player in computer.
NOTE: This example is not an actual example of DiamondScript, I will add more code.

```
<start>
*This is the beginning tag above* 

*This is a comment, it can be use for single line and multy-line*

import Player.control,
import Sprite, *Add "," if your want to import other thing from the same library*
import Score from Game
import Second from Time

*This the draw function defined below*
function (draw){
    start.background(rgb(0,0,0) *This starts the background*
    create class (Ball) *This creates a class*
    class Ball {
        when (start){
	    set (Score) to (0)
	    go to (Ball, 0, 0)
	    point direction (Ball, 45)*
	    forever:{ *forever loop*
		move.FORWARD (Ball, 15)
		on edge (BOUNCE)
	    }
	    
	    forever:{
		if (touching playerPaddle){
		    change (Score) by (1)
		    turn (180)* RIGHT
		    move.FORWARD (15)
		    wait (0.5) *This uses seconds*
		}
	     }
         }
     }

    create class (playerPaddle)
    class playerPaddle {
        when (start){
	    forever:{
	        set x to (MOUSE x)
	    }
	 }
     }

    create class (Line)
	class Line{
	    forever:{
		if (touching Ball){
		    STOP (all)
		}
	     }
         }
}
*This is the ending tag below*
<end>
```

If you ever wonder if DiamondScript can be use to make website or to turn this game to a game in a website, I could make it but what do yall think.
_But if you want to starting programming in DiamondScript, go to [Table of Contents](Table of Contents/main.md)_
