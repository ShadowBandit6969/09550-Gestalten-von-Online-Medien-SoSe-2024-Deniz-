Project Description

This project is a dynamic sketch for architecture, created using the p5.js library, a library that makes coding interactive graphics and animations “simple”. 
The sketch simulates the movement of three plotter heads that draw lines on the canvas (like an architect’s sketch), creating a generative art piece. 
The plotter heads move randomly, bouncing off the edges of the canvas and are connected by each other.

Algorithm Description
The algorithm involves the following steps:
1. Initialization: 
   - Three plotter heads (`plotterHead`, `plotterHead2`, `plotterHead3`) are initialized at random positions.
   - Each plotter head is assigned to a random direction vector (`direction`, `direction2`, `direction3`), which are deciding their movement.
   - The direction vectors are multiplied by a random factor to increase speed.
2. Drawing Loop:
   - The `draw` function is called repeatedly to update the canvas.
   - Each plotter head's position is updated by adding its direction vector.
   - A line is drawn from the plotter head's previous position to its new position.
   - If a plotter head reaches the edge of the canvas, it bounces back by inverting the corresponding component of its direction vector.
3. Reset Mechanism:
   - The sketch resets itself every 5 seconds, reinitializing the plotter heads and their directions to maintain a dynamic and continuously evolving drawing.

Technology Used
- HTML5: The structure of the web page.
- JavaScript: The main programming language used.
- p5.js: A JavaScript library for creative coding, enabling the creation of the interactive sketch.
- CDN for p5.js: The p5.js library is included via a CDN link, ensuring easy access.


End Product
The end product is an interactive web page that displays a continuously evolving generative art piece. 
The artwork is created by three plotter heads moving and drawing lines on an 800x800 canvas. 
The movement is random and the plotter heads bounce off the edges of the canvas, creating intricate and unique patterns over time. 
The sketch resets every 5 seconds, providing a fresh start and new patterns, ensuring that the visual output is always changing.
