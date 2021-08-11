
# Our Topic is Matplotlib:

![matplotlib](https://miro.medium.com/max/1120/0*JzkFEmn0jqM_M7Wm.)

## What is  Matplotlib?

- Matplotlib is a Python package used for 2D-graphics.

## Changing the default;

- Matplotlib comes with a set of default settings that allow customizing all kinds of properties. 

- You can control the defaults of almost every property in matplotlib: 
1-figure size and dpi.
2-line width, color and style.
3-axes, axis and grid properties.
4-text and font properties.

### Another thing we can set is Setting limits:

- If the Current limits of the figure are a bit too tight and we want to make some space in order to clearly see all data points
- we can use ; **xlim()** command **ylim()** command

## Adding a legend:

- This only requires adding the keyword argument **label** (that will be used in the legend box) to the plot commands


## Figures, Subplots, Axes and Ticks:

- We can have more control over the display using figure, subplot, and axes explicitly

### Figures:

- A figure is the windows in the GUI that has "Figure #" as title. Figures are numbered starting from 1.
- There are several parameters that determine what the figure looks like for example figsize, num and facecolor.


### Subplots

- With subplot you can arrange plots in a regular grid.
- You need to specify the number of rows and columns and the number of the plot.

### Axes

- Axes are very similar to subplots but allow placement of plots at any location in the figure

### Ticks

- Well formatted ticks are an important part of publishing-ready figures.
- Matplotlib provides a totally configurable system for ticks. 
- There are tick locators to specify where ticks should appear and tick formatters to give ticks the appearance you want.


## Animations:

- The most easy way to make an animation in matplotlib is to declare a FuncAnimation object that specifies to matplotlib what is the figure to update, what is the update function and what is the delay between frames.

## Other types of plot:

1- Regular Plots

2- Scatter Plots (`plt.scatter()`)

3- Bar Plots (`plt.bar()`)

4- Imshow (`plt.imshow()`)

5- Pie Charts (`plt.pie()`)

6- Quiver Plots (`plt.quiver()`)

7- Multi plot (`plt.subplot()`)