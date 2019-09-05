# udacity-and-One-Million-Arab-CodersPixel-Art-Maker
udacity and One Million Arab CodersPixel Art Maker lab

Pixel Art Maker
Task
You create a one-page web application that lets users draw a pixel image on a customizable panel.

To begin, you'll be given starter code (including HTML and CSS) to build the application. You'll write JavaScript code that lets the user create a grid of squares representing their design, and apply colors to those squares to create a digital masterpiece!

Your users should be able to:

Dynamically set the size of the table as an _N_ by _M_ grid.
Choose a color.
Click a cell in the grid to fill that cell with the chosen color.
Your primary task is to implement the makeGrid() function, that dynamically creates a grid that the user can interact with.

Key Takeaways
Accessing DOM elements using the `document` object methods
Define functions and append them to DOM elements as event listeners
Code nested loops to delete and create a table based on user input

Instructions
Get the Starter Code
If you'd like to start from scratch without any files, feel free to do so! You learn the most by developing on your own! But, it can be a bit challenging having to start from scratch, so we do provide some starter code to use.

The starter code includes all required HTML input fields, as well as some basic styling. A skeleton of the makeGrid() function is provided as well.

Development Strategy
Before writing any code, try loading up index.html from the starter project to see how things look! Notice that the design.js file is implemented in the <body> tag in the index.html file. Your goal is to build out the design.js file to achieve all the interactive elements on the page!

Now, open up design.js. As you start writing your code, keep these three tasks in mind:

Define your variables by selecting the DOM elements that the user will interact with. This is where your DOM skills can come into play! For instance, the submit button, the table, and the color picker need to be accessed. The value of the color selected needs to be stored as well, since the clicked cell in the table needs to be set to the selected color.
Add event listeners to the relevant DOM elements, so that user input can be color values and table sizes can be dynamically set by the user.
Set the size of the cross stitch canvas as an _N_ by _M_ grid with the makeGrid() function. Use your knowledge of JavaScript loops to dynamically clear and create the table based on user input. Each cell should have an event listener that sets the background color of the cell to the selected color.
Now test it! When you're done, you should be able to create a canvas of any size, choose a color using the color picker, and click on the canvas's table cells to set their color.

Note: To complete Pixel Art Maker, you must be using the current version of Edge, Firefox, or Chrome. Due to implementation differences, this exercise does not work effectively in Safari or Opera.

Udacity Style Guides
The starter contains basic styling, but feel free to style the app as you please! You should write your code and markup to meet the specifications provided in these style guides:

CSS Style Guide
HTML Style Guide
JavaScript Style Guide
Git Style Guide
