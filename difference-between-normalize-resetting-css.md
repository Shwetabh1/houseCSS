#Normalizing
-Aim is to make styling consistent across all browsers.
-Normalizing preserves useful defaults. [Major difference]
-Normalize.css corrects some common bugs.
[Example] SVG overflow in IE9
-Normalize.css doesn’t clutter your debugging tools.
A common irritation when using reset.css is the large inheritance chain that is displayed in browser CSS debugging tools. This is not such an issue with normalize.css because of the targeted stylings.

#Resetting
Each browser implements the CSS in their own way.
"In the beginning there was no standardisation on how styles worked, each browser implemented what it felt was right."
The goal of a reset stylesheet is to reduce browser inconsistencies in things like default line heights, margins and font sizes of headings, and so on. 

#Difference
CSS resets aim to remove all built-in browser styling. Standard elements like H1-6, p, strong, em, et cetera end up looking exactly alike, having no decoration at all. You're then supposed to add all decoration yourself.

Normalize CSS aims to make built-in browser styling consistent across browsers. Elements like H1-6 will appear bold, larger et cetera in a consistent way across browsers. You're then supposed to add only the difference in decoration your design needs.