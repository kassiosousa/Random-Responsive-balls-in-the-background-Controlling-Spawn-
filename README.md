# Random Responsive balls in the background (Controlling Spawn Area)
Random Responsive balls in the background (Controlling Spawn)

Working:
- In the main arquive (index.html) the div "area_ball" is the area when the balls will appears randomically, configure the size of area in the "balls.css" and the behavior in the "balls.js", like bellow.-

Variables in "balls.js":
- const colors: You can change the random colors that will apear in the balls
- const numBalls: Define the number of balls that will spawn in the screen

If you already have a div ID and want to attach the balls in there, just change the line:
document.getElementById("area_ball").append(ball);
And replace the id "area_ball" fot the ID that you already have created.

Credits: https://codepen.io/nashvail/details/wpGgXO#forks
