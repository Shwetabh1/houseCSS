@media all
@media screen, print {
	
}

body {
  background: hotpink;
}

//Simple AND 
@media screen and (max-width: 650px) {
  body {
    background: rebeccapurple;
  }
}

//Multiple AND
@media screen and (min-width: 481px) and (max-width: 960px) {
  /* ... */
}
//
//
@media (orientation: portrait), (min-width: 3rem) and (max-aspect-ratio: 2/1) {
  /* ... */
}
/* ----------- iPhone 5, 5S, 5C and 5SE ----------- */
/* Portrait and Landscape */
@media only screen 
  and (min-device-width: 320px) 
  and (max-device-width: 568px)
  and (-webkit-min-device-pixel-ratio: 2) {
}