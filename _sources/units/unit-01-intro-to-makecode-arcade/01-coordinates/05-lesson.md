![header](assets/header.png)

# Lesson: The MakeCode Arcade Display

In MakeCode Arcade, the **coordinate system** differs from the Cartesian plane's coordinate system. The x-axis is still the horizontal axis, and the y-axis is the vertical axis. The significant difference is that the origin `(0, 0)` is not in the screen's center but in the screen's upper-left corner. All visible coordinate points are `(+, +)` on the MakeCode Arcade display. This is displayed in the image below:

## The MakeCode Coordinate System

As mentioned above, the MakeCode Arcade Coordinate System has the origin `(0, 0)` in the upper-left corner.  The x-axis is the horizontal axis, and the y-axis is the vertical axis. **All visible points are positive in the MakeCode Arcade coordinate system**. Any negative coordinates will make the object render off of the display. This is displayed in the figure below:

![makecode-arcade-plane](assets/makecode-arcade-plane.png)

The remaining points going counterclockwise are `(0, 119)` in the lower-left corner, `(159, 119)` in the lower-right corner, and `(159, 0)` in the upper-right corner. This is displayed in the figure below:

![makecode-arcade-screen-coordinates](assets/makecode-arcade-screen-coordinates.png)

---

## Practice: Drawing a Rectangle in MakeCode

### 1. Plan the Plot of the Rectangle

Use the MakeCode Arcade Screen Grid to plot the four points of each corner of the rectangle.

![makecode-arcade-draw-square-grid](assets/makecode-arcade-draw-square-grid.png)

![makecode-arcade-draw-square](assets/makecode-arcade-draw-square.png)

To produce the 

### Algorithm 

1. Draw line from (0, 0) to (0, 119)

![makecode-arcade-draw-square-algorithm-01](assets/makecode-arcade-draw-square-algorithm-01.png)


2. Draw line from (0, 119) to (159, 119)

![makecode-arcade-draw-square-algorithm-02](assets/makecode-arcade-draw-square-algorithm-02.png)

3. Draw line from (159, 119) to (159, 0)


![makecode-arcade-draw-square-algorithm-03](assets/makecode-arcade-draw-square-algorithm-03.png)

4. Draw line from (159, 0) to (0, 0)


![makecode-arcade-draw-square-algorithm-04](assets/makecode-arcade-draw-square-algorithm-04.png)


![makecode-arcade-rectangle-code](assets/makecode-arcade-rectangle-code.png)

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://arcade.makecode.com/#pub:S11419-05415-57671-83863" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

