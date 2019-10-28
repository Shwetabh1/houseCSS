What are the different dimensions supported in CSS?

Viewport units were introduced with the CSS Values and Units level 3 spec. They allow to size elements and font sizes as a percentage of the total width or height of the user’s screen (the viewport).

em: 1em is the same as the font-size of the current element (more specifically, the width of a capital letter M.) The default base font-size given to web pages by web browsers before CSS styling is applied is 16 pixels, which means the computed value of 1em is 16 pixels for an element by default. But beware — font sizes are inherited by elements from their parents, so if different font sizes have been set on parent elements, the pixel equivalent of an em can start to become complicated. Don't worry too much about this for now — we'll cover inheritance and font-sizing in more detail in later articles and modules. ems are the most common relative unit you'll use in web development.

rem: The rem (root em) works in exactly the same way as the em, except that it will always equal the size of the default base font-size; inherited font sizes will have no effect, so this sounds like a much better option than ems, although rems don't work in older versions of Internet Explorer (see more about cross-browser support in Debugging CSS.)

