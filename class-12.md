
# Charts

A chart is a graphical representation for data visualization, in which "the data is represented by symbols, such as bars in a bar chart, lines in a line chart, or slices in a pie chart". A chart can represent tabular numeric data, functions or some kinds of quality structure and provides different info.


![charts](https://media.gcflearnfree.org/ctassets/topics/234/chart_type_1.png
)

## **Drawing  line chart** 

### What is a Line Chart?
 
A line chart is a style of chart that is created by connecting a series of data points together with a line. It is used to display information in a series of data points connected by straight line segments. It enables us to find trends (or patterns) over time.
 
### Use of the Line Chart?
 
A line graph is used to represent a set of data values in which a quantity varies with time. We can use a line chart to show how the stock value for a certain company develops over time on the stock market. We can also use it for representing temperature, sales, employment, company profit or cost over a period of time.



## **Drawing pie chart** 

### What Is a Pie Chart?

A chart is a statistical tool used to graphically represent numerical data. A pie chart displays that numerical data as a circle divided into slices. The size of each slice is proportional to the numeric value that it stands for.

### Use of the Pie Chart?

- first we need the canvas element

- after that we need to get the context and to instantiate the chart

- next we need to create the data , this data will be different to the line chart

- after the pie data we will add option



## **Drawing bar chart** 

### What Is a bar chart?

Bar graph is the simplest way to represent a data.

In consists of rectangular bars of equal width. 

● The space between the two consecutive bars must be the same. 

● Bars can be marked both vertically and horizontally but normally we use vertical bars.

### Use of the bar chart?

- first we will add the canvas element

- next we retrieve the element and create the graph

- finally we add in the bar chart's data

![chartsin](https://image.slidesharecdn.com/random-151102200246-lva1-app6892/95/charts-graphs-and-tables-2-638.jpg?cb=1446494781
)


## **Basic usage of canvas** 

![charts](https://www.webfx.com/blog/images/assets/images.sixrevisions.com/2010/10/03-01_html5_canvas_element_ld_img.png
)

### The canvas element

At first sight a looks like the  element, but the difference being that it doesn't have the src and alt attributes. Indeed, the canvas element has only two attributes, width and height.

### Required vanvas tag

> the canvas element requires the closing tag.

### The rendering context

***in 2D rendering canvas element has method called getContext() used to obtain the rendering context and its drwing function and it takes one parameter.***

### Drawing rectangles

- fillRect(x, y, width, height) : Draws a filled rectangle

- strokeRect(x, y, width, height) : Draws a rectangular outline

- clearRect(x, y, width, height) : Clears the specified rectangular area, making it fully transparent

### Drawing paths

- beginPath() : Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up

- Path methods : Methods to set different paths for objects

- closePath() : Adds a straight line to the path, going to the start of the current sub-path

- stroke() : Draws the shape by stroking its outline

- fill() : Draws a solid shape by filling the path's content area


### Moving the pen

- moveTo(x, y) : Moves the pen to the coordinates specified by x and y.

- When the canvas is initialized or (beginPath()) is called, you typically will want to use the (moveTo()) function to place the starting point somewhere else. We could also use (moveTo()) to draw unconnected paths.

### Lines

*lineTo(x, y) : Draws a line from the current drawing position to the position specified by x and y.*


HI ... my name is Ola 23 years old i'm a Nutritionist and my computer operating system version number is windows 10 and i'm so excited for this course because i want to learn something very important to me 

click on the [link](https://github.com/olaaltaslaq) to find my GitHub

