# one_pager

A simple One Pager easy to include in every Project

AUTHOR: AICHBAUER LUKAS

email: rudolfson.junior@gmail.com

***

## how to use

***

import the css and the js file to your html file.

don't forget to import jQuery in your project... import it in front of the img_slider.js

    <link rel="stylesheet" type="text/css" href="http://localhost/tuts/img_slider_tut/css/img_slider.css" />
    <script type="text/javascript" src="http://localhost/tuts/img_slider_tut/js/JQUERY.js"></script>
    <script type="text/javascript" src="http://localhost/tuts/img_slider_tut/js/img_slider.js"></script>

create a navigation and divs with the class "onepage".

also add ids to the divs, you can name your ids whatever you like,

the important thing is to link your a tags to the ids of the divs.

If you want a home section, create a 

    <div class="onepage" id="home">

and in your nav add an anchor to home like

    <a href="#home" > Home </a>

if you download this project with the index file and set your paths

the css and js and also to jquery than this project works from scratch.


This is a basic structure of a one pager. 

    <nav>
      <ul>
        <li><a href="#first">First</a></li>
        <li><a href="#second">Second</a></li>
        <li><a href="#third">Third</a></li>
        <li><a href="#">Third</a></li>
      </ul>
    </nav>
    <div class="onepage"  id="first">
    </div>
    <div class="onepage" id="second">
    </div>
    <div class="onepage" id="third">
    </div>
