---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of norway by justin zayas

## Describe your program

-  I desgin this for norway.
- I excepted a practiconer because of how this is the practitoner level.


## Current output

-   
* * *
![Flag](/images/final flag.png)
* * *

## Describe your process.

-   The process took me aleast two weeks to do and had help from julian and mr allatta and question i had questions like how do i create rectangles and how does this make the shape of the flag. 


## Explain your code.

-  (overlay
 (put-image
  (rectangle 30 200 "solid" "blue")
  100 100 
  (rectangle 300 200 "outline" "black"))
 (put-image
  (rectangle 300 30 "solid" "blue") 
           150 100 
           (rectangle 300 200 "outline" "black"))_
-  This shows the first part  of the flag that is shown to be a differentthis process show that its a bunch of overlay and put image. this functions independently by running as it own program and they work in milliseconds and that with code like put-image and overlay which can connect to the image or flag that you are trying to make in any code that different than wescheme.
-   

* * *

```
(overlay
 (put-image
  (rectangle 30 200 "solid" "blue")
  100 100 
  (rectangle 300 200 "outline" "black"))
 (put-image
  (rectangle 300 30 "solid" "blue") 
           150 100 
           (rectangle 300 200 "outline" "black")) 
 (put-image
  (rectangle 50 200 "solid" "white") 
  100 100 
  (rectangle 300 200 "outline" "black")) 
 (put-image(rectangle 300 50 "solid" "white") 
           150 100 
```

* * *

-  Each argument shows how they can make rectangles and colors too show how this can ake at least 3/4 of the norway flag.
-  This shows how this could fit onto the page by scaling the image or changing the size of the rectangles and changing the colors.
 



## Program code

```overlay
 (put-image
  (rectangle 30 200 "solid" "blue")
  100 100 
  (rectangle 300 200 "outline" "black"))
 (put-image
  (rectangle 300 30 "solid" "blue") 
           150 100 
           (rectangle 300 200 "outline" "black")) 
 (put-image
  (rectangle 50 200 "solid" "white") 
  100 100 
  (rectangle 300 200 "outline" "black")) 
 (put-image(rectangle 300 50 "solid" "white") 
           150 100 
           (rectangle 300 200 "outline" "black")) 
 (rectangle 300 200 "solid" "red"))
;(define shapes)

(define stripe1 (rectangle 30 200 "solid" "blue"))
(define stripe2 (rectangle 300 200 "outline" "black"))
(define stripe3 (rectangle 300 30  "solid" "blue"))
(define stripe4 (rectangle 300 200 "outline" "black"))
(define stripe5 (rectangle 50 200 "solid" "white"))
(define stripe6 (rectangle 300 200 "outline" "black"))
(define stripe7 (rectangle 300 50 "solid" "white"))
(define stripe8 (rectangle 300 200 "outline" "black"))
(define stripe9 (rectangle 300 200 "solid" "red"))

```
