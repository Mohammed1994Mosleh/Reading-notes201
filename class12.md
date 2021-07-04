# Reading class12:
## Char.js:
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.
![chart.js](https://cdn.mos.cms.futurecdn.net/S5bicwPe8vbP9nt3iwAwwi.jpg)
- Creating a Chart:
It's easy to get started with Chart.js. All that's required is the script included in your page along with a single canvas node to render the chart.






### The <canvas> element:
At first sight a canvas looks like the img element, with the only clear difference being that it doesn't have the src and alt attributes. 
![canvas](https://miro.medium.com/max/1016/1*YkKgLfAJc1Q_ln737HkHYA.png)

### Drawing shapes with canvas:
- The grid:
Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0).
- Drawing rectangles:
 There are three functions that draw rectangles on the canvas:
 1. fillRect(x, y, width, height)
 2. strokeRect(x, y, width, height)
 3. clearRect(x, y, width, height)

- Drawing paths:
 path is a list of points, connected by segments of lines that can be of different shapes.
 1. First, you create the path. beginPath()
 2. Then you use drawing commands to draw into the (pathPath methods).
 3. Once the path has been created, you can stroke or fill the path to render it.

- Linesl:
For drawing straight lines, use the lineTo() method.
- Arcs:
To draw arcs or circles, we use the arc() or arcTo() methods.
- Bezier and quadratic curves:
                            quadraticCurveTo(cp1x, cp1y, x, y) 

                            bezierCurveTo(cp1x, cp1y, cp2x, cp2y, x, y)

#### Applying styles and colors:
there are two important properties we can use:
1. fillStyle = color:
Sets the style used when filling shapes.
2. strokeStyle = color:
Sets the style for shapes' outlines.


#### Transparency:
we can draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.
                            globalAlpha = transparencyValue 


#### Gradients:
 we can fill and stroke shapes using linear, radial and conic gradients. We create a CanvasGradient object by using one of the following methods.
 - createLinearGradient(x1, y1, x2, y2)
 - createRadialGradient(x1, y1, r1, x2, y2, r2)
 - createConicGradient(angle, x, y).

   ![canvas examples](https://flaviocopes.com/canvas/Screen%20Shot%202018-10-28%20at%2014.38.54.png)

 #### Patterns:
  to create a pattern of images the createPattern() method.
                                  createPattern(image, type)


#### Drawing text:
The canvas rendering context provides two methods to render text:
- fillText(text, x, y [, maxWidth])
- strokeText(text, x, y [, maxWidth])

##### Styling text:
There are some more properties which let you adjust the way the text gets displayed on the canvas:
- font = value
- textAlign = value
- textBaseline = value
- direction = value

##### Advanced text measurements:
- measureText():
Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.
