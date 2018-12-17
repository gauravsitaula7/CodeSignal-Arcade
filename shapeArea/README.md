Below we will define an `n`-interesting polygon. Your task is to find the area of a polygon for a given `n`.

A `1`-interesting polygon is just a square with a side of length `1`. An `n`-interesting polygon is obtained by taking the `n - 1`-interesting polygon and appending `1`-interesting polygons to its rim, side by side. You can see the `1`-, `2`-, `3`- and `4`-interesting polygons in the picture below.

![alt text](https://github.com/Lintik/Arcade/blob/master/Intro/Edge%20of%20the%20Ocean/shapeArea/area.png)

__Example__

* For `n = 2`, the output should be <br /> `shapeArea(n) = 5`;
* For `n = 3`, the output should be <br /> `shapeArea(n) = 13`.
