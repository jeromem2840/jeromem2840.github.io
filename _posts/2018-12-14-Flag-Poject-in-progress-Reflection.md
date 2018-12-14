---
layout: post
title: "Flag v2"
date: 2018-12-14
---
This is the code i have so far for my flag 
```
(define size 100)
(define width(* 6 size))
(define height(* 3 size))
(define stripeheight(/ height 5))
(define Base (rectangle width height "solid""whitesmoke"))
(define stripe (rectangle width stripeheight "solid" "red" ))
(define x (/ width 3))
(define y (/ height 2))
(define stage1 (put-image stripe x y Base))
```
This is what it produces 
![Flagimage](/images/Flag V2.png)
Looking back this was a very tedious process because of the the way you have to really look into positioning of stripes and geting it not to be inverted on the wrong side i asked so many questions i could write a book on it like how to get it in the right postion how to get the stripe to be on the flag instead of off of the screen but looking back all of those questions got me to the ponit i am now with a semi decent flag.
