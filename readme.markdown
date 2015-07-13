# Udacity Front-End Nanodegree Project 1 #

## Goals ##

## Notes ##

There are two different pages here - one that uses bootstrap and one that relies only on flexbox.

### Bootstrap Version ###

* The 3 furball pictures each have 4 images. 
	* There are 3 pictures for when `<picture>` is supported, and a fallback default picture for when it isn't. 
	* 2 pictures are for when Bootstrap displays in the grid system - 992 and 1200 pixels.
	* 1 picture is for when Bootstrap displays everything in 1 long column. 
	* 1 is the default image. In order to accomodate a wide range of screen sizes while still keeping a small file size, the default image is larger than the 2 images for gridging but smaller than the image for when all column sizes take up the whole row.

* The splash image has two different images. The smaller is the default for when the picture element is not supported.

* `margin-top` is deliberately used for `.page-header` in `main.css` (instead of the recommended margin shorthand), as it is intended to only override the top value of `margin` as defined in `bootstrap.css`
	* the same is true for header margins

## Questions ##

### Bootstrap Version ###

* `responsive.css` has: 
<blockquote>.furball_image {
    min-width: 300px;
}</blockquote>
   This ensures, when the viewport is from 992-1199 pixels wide, the furball images take up the amount of space they were made for. I could not really fiugre out why they were not taking up 300px without that - especially because I threw in a huge image 3 times to decide to use 300px. (The large image displayed 3 times was displayed at 300px wide across) 

## Images ## 

Unless otherwise specified, all images are my own.

