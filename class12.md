# Welcome to reading notes code 201 class 12:
 
## First we will talk about charts

![chart image](https://raw.githubusercontent.com/ankitkanojia/DotNetCharts/master/chart.jpg)

- We can say about chart that they are an organized way of displaying data in a structured layout.

- We have many forms like :
  -**Radar Chart**.
  -**bar charts**.
  -**line charts**
  -**pie chart** 
  -**Bubble Chart**.

- We can add them using javascript plugin called **chart.js**.
       -we can get it from  **npm** , the**GitHub releases** , or use a **Chart.js CDN** .

### We will have a small example on how we can add line chart using chart.js.

**How to add line chart?**

1-First you need to create a canvas element in our HTML.
2-Then we add script tag that will retrieve the context of the canvas.
3-Inside the javascript page we add the code building the data we want to display using objects and arrays.

## Now, let’s talk about < canvas > element:

- It’s a similar tag element to image but with the main difference is that it dosen’t have attribute src.

- We have what called the **fallback content** as an alternate content, which is displayed in older browsers not supporting it.

**Drawing shapes with canvas**
- By default canvas element has *150 pixels* wide and *150 pixels* high.
-The coordinate space in canvas is called *grid* and normally 1 unit in the grid corresponds to 1 pixel on the canvas.
- Canvas element only supports two shapes: *rectangles and paths* , which are lists of points connected by lines.

- For example if we want to draw rectangles we use the one of the following functions;

- **fillRect(x, y, width, height)**
- Draws a filled rectangle.

- **strokeRect(x, y, width, height)**
- Draws a rectangular outline.

- **clearRect(x, y, width, height)**
- Clears the specified rectangular area, making it fully transparent

### In order to create shapes using paths, we take some extra steps:
- First, you create the path.
- Then we draw into the path using drawing commands.
- Once the path has been created, you can fill the path to render it.

- Some of the functions which are needed for creating paths:

**beginPath()**
- Creates a new path. 

**Path methods**
- Which they are Methods used to set different paths for objects.

**closePath()**
- Adds a straight line to the path, going to the start of the current sub-path.

**stroke()**
- Draws the shape by stroking its outline.

#### Any other shapes must be created by combining one or more paths using functions.
