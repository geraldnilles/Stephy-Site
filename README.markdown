Stephy Site
===========

# Goal
Create a new version of stephy's site hosted on Google App Engine.

# Overview
The site will be very picture-based.

Each page will have an instagram-like background picture.  She has many already on her current site.  A subtle filter will be applied to the picture to add contrast.  On top of the picture will be the page text in white.

Changing pages will continue to be done using AJAX.  Each time a page is changed, the background image will also be modified.  I might even make the background image randomly change each time to give the site a dynamic flow.

# Background Image Format
It will be a JPEG image with a set minimim size.  The images will be cropped and resized to meet 2 formats: Desktop and Mobile.  The Desktop version will be landsakp and the mobile will be portrait.  When a new background image is uploaded, the user will be asked how to crop it. 

The cropping could also be done purely in Javascript.  It could check the screen dimentions and make sure the Point of Interest is in the center of the screen.   

I will need to figure out a clever way of making the site function on both desktop and phone formats.  

