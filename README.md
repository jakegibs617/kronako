
<!-- run server -->
$ hugo server -D
<!-- http://localhost:1313/projects/veracode/ -->

<!-- to create a new item -->
$ hugo new paintings/2-8.md
<!-- hugo new project-name/item.md -->



<!-- go here to get css classes -->
https://www.w3schools.com/w3css/default.asp


<!-- notes -->
- create dir in layouts for projects and define list for that project


-Lightbox shortcodes:
<!--
The shortcode uses named arguments because I wanted some of them (such as width and center) to be optional. The arguments are:

name: Required argument which is the name of the image resource to load. Note: To tell Hugo to search for any file that includes the name and return the first hit, use wildcards, as in the example below.

title: The title of the image. Used by the alt tag and by Lightbox.

width: An optional width to override the element’s width.

class: An optional argument to add a custom class to the figure.

centered: An optional argument which, if it exists and has any value, will wrap the image and link in a div with a center class. -->