# js_css_animation
1. GSAP JavaScript Animation Library


My very first exposure to the GSAP libraries was when I created this cookie pop-up inspired by the developedbyed tutorial: https://www.youtube.com/watch?v=r1iul4uRFuE&t=2391s
A cookie svg was selected from the svgrepo website then the parts of the cookie (such as the crumbs) were grouped in Figma to facilitate the implementation of the CSS and JS code. Another amazing feature of Figma is that we can export layer names using the id attribute. This helped when styling the cookie in VS code. 
To access the GSAP  libraries, the first GSAP cdn script tag from https://cdnjs.com/libraries/gsap  was copied and pasted into the HTML file, and in the JS file, some codes were implemented, creating some interesting effects. Overall, I liked how easy and short it was to implement different animation features using GreenSock.  I have tried different effects and manipulated the values to better understand how each effect works.

JS Animation key points:

x axis= animate element horizontally

x: 0 = element stays to its actual position

x: +ve = element moves to the left
 
x: -ve = element moves to the right

y axis = animate element vertically

y: 0 = element stays to its actual position

y: +ve = element moves to the bottom

y: -ve = element moves to the top










2. Learn to build an SVG animation using CSS


The bike svg animation was created using CSS.  Inspired by the tutorial: https://www.youtube.com/watch?v=gWai7fYp9PY&t=981s , I created my own SVG animation.
 In Figma, using the pen tool, I added an oval background with a linear color gradient of blue and purple. Then, I grouped the layers I chose to implement in CSS, i.e., cap, grocery, woman-bike, front-wheel, and back-wheel. The SVG image was exported with the layer names as id attributes and the path was copied and pasted into the HTML file.
In the CSS file, I selected the id selector I wish to implement and gave each of them an animation name which was then used in the  @keyframe rule to specify the animation effect. For this practice, I have mainly worked with the transform property with value rotate(), rotatex(), rotatey(), rotatez(), translate(),  translatex(), translatey(), translatez().

CSS Animation Key points:

rotatex() = rotates an element around the horizontal axis without deforming it.

rotatey() = rotates an element around the vertical axis without deforming it.

rotatez() = rotates an element around the z-axis without deforming it.










3. SVG Animation with CSS

In Figma, using the polygon tool, three triangles were drawn. Each has an opacity of 75%.  To facilitate the implementation of the css code the layers were given meaningful names. Then the appropriate layers were grouped to create a duotone icon, creating a g element in the SVG code. which was exported with the id attribute to html.
 In the CSS file the ids of each triangle were targeted and were told to animate automatically using the  transition property with value " all 1s ease" which tells CSS to animate all elements over a duration of 1s with a timing function of ease. Targeting the hover event of each triangle, we implemented the transform property with translateX value. Using this declaration the triangle will move back and forth.
CSS Animation Key points:
translateX(-y%)= moves icon y% to the left
translateX (y%) to the right.
 Using JavaScript, the color of the triangle was changed dynamically.

