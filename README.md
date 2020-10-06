# Path Generator

Repository containing a piecewise path generator, the function `pathgen` computes the right and left path from a set of points in two dimensions. This function takes two vectors `x` and `y` as arguments, defining the central piecewise-linear path. The coordinates of the right and left piecewise-linear paths are returned as outputs.

```python
(x_r, y_r, x_l, y_l) = pathgen(x, y)
```

An optional argument can be passed to the function to define the deviation between the central path and the lateral paths.