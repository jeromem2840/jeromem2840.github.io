---
layout: post
title "My Video Game "
date: 2019-03-09
---

Jerome Morene

Shared link to your game:
https://www.wescheme.org/view?publicId=asSwQ9HgqX

Game Title: 
hOtEl MaRio

Describe your game, characters and setting: 
Originally mario was supposed to be in a hotel defending it but than i changed it to just the mushroom kingdom.

Choose one of either the onscreen?, update-player, distance, or collide? functions. Copy and paste the entire function including contract, purpose statement, examples and definition. 
; onscreen? : Number -> Boolean
; Determines if the coordinate is on the screen

;; EXAMPLEs:
(EXAMPLE(onscreen? 275)true)
(EXAMPLE(onscreen? 420)true)
(define (onscreen? x)
(and  (safe-left? x)
  (safe-right? x)))


Describe every line in the pasted code above.
1.This is the contract of the onscreen function
2.This is describing what the contract above does
4.This is my first example of the onscreen function so i put in a coordinate that is in the video game that determines if my character is onscreen at the time.It also has a boolean at the end which is basically turning the line of code into a true or false statement.
5.This example is basically the same as the last line of code but instead it has a new coordinate from the game.
6.This is the definition of the function onscreen this is actually putting the function  to work in game and it has to match the way the examples work because the example is what i expect the function to do and the definition is how it actually works.
7.This is the and function in my program the and function to put it simply is a stepping stone to incorporate more specifics into my function so this incorporates the other function safe-left? Which is a whole explanation in itself but in short it makes sure the boundaries of the game are identified
8.This is almost the same as line 7 but this part applies to the opposite function safe-right? Which does the same thing as safe-left but just defines the boundary on the right side.


Describe the role of the function in the video game program.
So what the onscreen function does in my game is it makes sure the player whenever the character is on a specific coordinate on the screen the character can be seen this is a important part of the game because it would be impossible to play if you can't see your character.  
