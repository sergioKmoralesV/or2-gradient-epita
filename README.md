# OR 2 - Gradient project - EPITA

### Nom: MORALES VILLARROEL
### Prenom: Sergio Kevin
---

### Solving the Gradient
For solving this problem we used mainly two libraries `matplotlib` and `numpy`. It helps us for the plotting and also for the linear algebra operations like the dot product.

Given a function `f(x,y) = x^3 * y + y^3 * x`

We calculated the gradient using the partial derivatives: 
`fx = 3 * y * x^2 + y^3`
and
`fy = 3 * x * y^2 + x^3`

### Capturing data
Then, we use the function `input` in order to get the values for both the vector `u` and the point `(x,y)`. To validate that the numbers are either `float` or `int`, we need to parse them to float and catch the error. Nevertheless, we do all the calculations using floats.

We also reject `fractions` because their treatment is different in python as `DataType`.

### Graphics
- We are first plotting the function f(x,y) with the point (x,y) in the plot.
- We present the gradient and the vector u (and u') using a 2D presentation using contour lines 

Thanks for the task!
