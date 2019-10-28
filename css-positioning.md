CSS Positioning

There are 5 types of positioning

1. fixed
2. absolute
3. relative
4. static 
5. inherit

How do they work?


1. fixed fixes it and doesn't move from its position. Doesn't affect the document flow and always stays on top.

2. Absolute is same but the position is fixed. When scrolling down it doesn't go down. It checks the left right positioning from margin. Incase of nested absolute it takes from parent element.

3. Relative: Affects the document flow and relative to its original position. Not the document margin.

4. Static : The default positioning. If you use left right etc after stating static it won't work.

5. Inherit: to overcome static.
ABSOLUTE POS DEMO HERE: https://jsfiddle.net/psb3zo7a/4/

Z-Indez allows us to control the stacking order. 
Demo Here: http://jsfiddle.net/ao0Lkupr/8/

Floating element removes it from normal document dlow and then takes that element and pushes it to the far left as possible other elements will move up as far as possible to flow around the element

clear : Takes it to the new line. Doesn't keep it in the same line of HTML Page.
Demo Here: http://jsfiddle.net/vrdszbwg/5/

How to Center an element

Demo Here: http://jsfiddle.net/tFscL/5195/

SQUARE IN A SQUARE
https://jsfiddle.net/ohyp7bLa/3/