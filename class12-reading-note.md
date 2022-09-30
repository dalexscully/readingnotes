# Reading-note-12
<hr>


## Chart.js, Canvas
<hr>

### JavaScript Canvas
<hr>

What does the canvas allow a developer to acheive? HTML5 features the canvas element that allows you to draw 2D graphics using JavaScript. The canvas element requires at least two attributes: width and height that specify the size of the canvas.

What is the importance of the closing canvas tag? The element requires the closing tag canvas. Any content between the opening and closing tags is fallback content that will display only if the browser doesn’t support the canvas element.

Explain what the getContext() method does. The canvas element features the getContext() method that returns a render context object. The getContext() takes one argument which is the type of context. For example, you use the "2d" to get a 2D rendering context object, which is an instance of the CanvasRenderingContext2D interface. The 2D rendering context allows you to draw shapes, text, images, and other objects. The following example shows how to select the canvas element using the querySelector() method and access the drawing context by calling its getContext() method.

Chart.js Documentation
What is Chart.js and how it can be brought into your project? Chart.js is an free JavaScript library for making HTML-based charts. It is one of the simplest visualization libraries for JavaScript, and comes with the following built-in chart types: Scatter Plot. Line Chart.

List 3 different Chart types you can create using Chart.js. The three different type of charts are as followed: Types of Charts

Bar graphs to show numbers that are independent of each other.
Pie charts to show you how a whole is divided into different parts.
Line graphs show you how numbers have changed over time.
Easily Create Stunning Animated Charts with Chart.js
What are some advantages to displaying data via a chart over a table? Instead of presenting data in precise values, charts show the patterns that emerge or relationships between different variables in bar or pie graphs. While charts may sacrifice some precision and granularity, they allow for a broader scope of high-level analysis and quicker comprehension of the data.

How could Chart.js aid your previously created applications visually? It makes the data more presentable and easy to understand. By looking at the chart itself one can draw certain inferences or analysis. It helps in summarizing a very large data in a very crisp and easy manner. It helps in better comparison of data.
