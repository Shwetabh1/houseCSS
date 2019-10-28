.content1 {
	box-sizing: content-box; /* This is by default */ 
}
#
This is the initial and default value as specified by the CSS standard. The width and height properties include the content, but does not include the padding, border, or margin. For example, .box {width: 350px; border: 10px solid black;} renders a box that is 370px wide.
#
#
The width and height properties include the content, padding, and border, but do not include the margin. Note that padding and border will be inside of the box. For example, .box {width: 350px; border: 10px solid black;} renders a box that is 350px wide. The content box can't be negative and is floored to 0, making it impossible to use border-box to make the element disappear.
Here the dimensions of the element are calculated as: width = border + padding + width of the content, and height = border + padding + height of the content.
https://jsfiddle.net/api/mdn/