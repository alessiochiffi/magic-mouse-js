
# MagicMouse.js

A lightweight javascript library to create some amazing effects for the mouse (cursor) on your website - MagicMouse.js : [https://magicmousejs.web.app/](https://magicmousejs.web.app)

![One of magic-mouse effects](https://user-images.githubusercontent.com/19908411/77246772-03384880-6c5d-11ea-8074-6975bc8e3632.gif)

# Installation
MagicMouse.js is a vanilla javascript library so you DON'T need to include any other library like jQuery.
You just need to include 2 things to your HTML :

### Put the CSS file to your head tag:

    <link rel="stylesheet" href="dist/magic-mouse.css" />


### Include the js file to the bottom of your HTML file (right before the end of body tag) :

    <script type="text/javascript" src="dist/magic_mouse.js"></script>

### Insert your options and initialize :

    <script type="text/javascript">
	    options = {
	        "cursorOuter": "circle-basic",
	        "hoverEffect": "circle-move",
	        "hoverItemMove": false,
	        "defaultCursor": false,
	        "outerWidth": 30,
	        "outerHeight": 30
	      };
	    magicMouse(options);
    </script>

### Hover effect :
If you want your mouse have elegant hover effect, don't forget to add the class "magic-hover" to the element you want it have hover effect, for example :

    <a class="magic-hover magic-hover__square">download</a>

# Configuration list (updating):
| Variable name | Value |
|--|--|
| cursorOuter | Default: "circle-basic", other options : "disable" |
| hoverEffect | default: "circle-move", other options : "pointer-blur", "pointer-overlay" |

# What's next?
You should have the nice effect for your mouse now, of course you can override the CSS code to make it more elegant and suitable with your website (change color, size,..).
I'll add more effects to this libs when I have time, sure you can contribute to this repository and I'm very appreciate that ! :)