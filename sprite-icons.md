##Definition
CSS Sprites are a means of combining multiple images into a single image file for use on a website, to help with performance.

##Advantage
While the total image size (sometimes) goes up with sprites, several images are loaded with a single HTTP request. Browsers limit the number of concurrent requests a site can make and HTTP requests require a bit of handshaking.

##How to use them?
Get the startposition x and Y
speicify the width and height and background position
Voila!

You got it.

Consider A Big Rrectangle: 

.flags-canada, .flags-mexico, .flags-usa {
  background-image: url('../images/flags.png');
  background-repeat: no-repeat;
}

.flags-canada {
  height: 128px;
  background-position: -5px -5px;
}

.flags-usa {
  height: 135px;
  background-position: -5px -143px;
}

.flags-mexico {
  height: 147px;
  background-position: -5px -288px;
}