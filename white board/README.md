**Whiteboard Web App**

**Whiteboard Preview**

This repository contains the code for a simple web-based whiteboard application that features an eraser and undo functionality. The whiteboard allows users to draw and erase using their mouse. The main objective of this project was to create a user interface resembling a traditional whiteboard and to implement the necessary functionality using JavaScript.

**Features**
**Draw:** Use the mouse to draw on the whiteboard.
**Erase:** Select the eraser tool to erase drawn content.
**Undo:** Remove the last drawn or erased element from the whiteboard.
**How it Works**
The functionality of the whiteboard is achieved through HTML, CSS, and JavaScript. Here's a brief overview of the technologies and concepts used:
**
**HTML****
The main structure of the whiteboard interface is built using HTML. The whiteboard itself is represented as a div element where the drawing and erasing take place.

**CSS**
CSS is used to style the whiteboard and create a visually appealing interface. Various CSS properties like background, border, and cursor are utilized to achieve the desired appearance. Additionally, styling is applied to the eraser tool and buttons.

**JavaScript Functionality**
The core functionality of the whiteboard is implemented using JavaScript. Here's how each of the main features is accomplished:

**Draw:** JavaScript listens for mouse events (such as mousedown, mousemove, and mouseup) on the whiteboard area. When the user holds down the mouse button and moves, the application draws lines by creating div elements with specific positions and styles.

**Erase:** The eraser tool is activated by clicking the eraser button. Similar to drawing, the JavaScript code listens for mouse events, but instead of drawing, it identifies the elements under the cursor and removes them, simulating erasing.

**Undo:** The undo functionality is implemented by keeping track of the drawing elements in an array. When the user clicks the undo button, the last element from the array is removed, effectively undoing the last drawing or erasing action.

**Hosted Link**
Check out the Live Demo to see the whiteboard in action.

