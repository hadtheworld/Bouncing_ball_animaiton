# Bouncing_ball_animaiton
In this project we are going to extensively use the animation to create an infinite animation of a Ball jumping over the Square Platforms coming and going in infinite look.

I have used @keyframes for animation and transform to change the position in x and y axis and to rotate the blocks as we will see in the animation.



The project is well divided into  components in form of classes to make square blocks and ball and different animations are applied on each component to give the realistic effect.



In this animation you can feel the shape of ball changing as it bounces which give a realistic effect of bouncing animation.



Key takeaways from the project:

   - writing well structured code in class format to give better formatting  to the components and apply styles and animation to only those components which you want to.

   - A new take on the animation using CSS and using delays in animation to give realistic effects to the animations.

   - HTML formatting and CSS styling to generate impressive results without any use of JavaScript
   
   **For deeper understanding of the code read from here on:**
This code is an HTML and CSS implementation of a bouncing ball animation. Let's go through it step by step.

**HTML:**

 - The document starts with a DOCTYPE declaration, which specifies the version of HTML being used.
 - The HTML document is wrapped in <html> tags, with the language attribute set to "en".
 - The <head> section contains various meta tags for specifying the character encoding, viewport size, and compatibility mode for Internet Explorer.
 - The title of the document is set to "Bouncing Ball".
 - The document references an external stylesheet called "bouncing_ball_style.css".
 - The <body> section contains a container <div> with a class of "wrapper", which will hold the animation elements.
 - Inside the wrapper <div>, there are three <div> elements. Two of them have a class of "block" and a class of "block-1" and "block-2" respectively, while the third has a class of "ball". These elements will be animated in the CSS.

**CSS:**

 - The universal selector (*) is used to set padding, margin, and box-sizing to 0 for all elements on the page.
 - The <html> element's font size is set to 62.5% for easier rem-based sizing.
 - The <body> element is set to be a grid container with its items centered horizontally and vertically. It also has a height of 100vh to make sure it covers the entire viewport.
 - The wrapper <div> has a fixed width of 70rem, an aspect ratio of 1, and a background image set to "bg.jpg". The position is set to relative, and overflow is hidden. The background size is set to "auto 70rem" and the background-repeat is set to "repeat-y". Finally, there is an animation called "bganim" that will move the background image up and down in a loop over 5 seconds.
 - The block elements have a width of 18rem, an aspect ratio of 1, and a background color of rgb(51,184,184). They are positioned absolutely with a box-shadow that gives them a 3D inset effect. The block-1 element is positioned at top: 16rem and right: 44rem. It has an animation called "block1anim" that moves it up and down, rotates it, and changes its opacity over 5 seconds. The transform-origin is set to bottom right. The block-2 element is positioned at top: 16rem and right: 8rem. It has an animation called "block2anim" that moves it up and down, rotates it, and changes its opacity over 5 seconds. The transform-origin is set to bottom left.
 - The ball element has a width of 12rem, an aspect ratio of 1, a background color of rgb(255,118, 118), and a border-radius of 50% to make it round. It is positioned absolutely at left: 29rem and top: 22rem. It has an animation called "ballanim" that moves it up and down, scales it, and changes its aspect ratio over 2.5 seconds.
 - There are three keyframe animations defined in the CSS: "bganim", "block1anim", and "block2anim". The "bganim" animation moves the background image up and down by changing its position. The "block1anim" and "block2anim" animations move the blocks up and down, rotate them, and change their opacity to create a pulsing effect. The "ballanim" animation moves the ball up and down, scales it, and changes its aspect ratio to create a bouncing effect.

**That's a step-by-step explanation of the code**
