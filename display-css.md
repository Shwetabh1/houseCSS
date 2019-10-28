##DISPLAY TAG##

display: flex;
display: none;
display: inline;
display: inline-block;
display: block;

#INLINE
The default value for elements. Think of elements like <span>, <em>, or <b> and how wrapping text in those elements within a string of text doesn't break the flow of the text.
An inline element will accept margin and padding, but the element still sits inline as you might expect. Margin and padding will only push other elements horizontally away, not vertically.
An inline element will not accept height and width. It will just ignore it
https://jsfiddle.net/shwetabh1/rs7tpbn4/1/

#INLINE_BLOCK
An element set to inline-block is very similar to inline in that it will set inline with the natural flow of text (on the "baseline"). The difference is that you are able to set a width and height which will be respected.

#BLOCK


#TABLECELL
There is a whole set of display values that force non-table elements to behave like table-elements, if you need that to happen.

#NONE
hides the element and also affects the flow. content moves up


