# Multinomial-modeling

## Function to model

![function](/function.png "Equation of the function")

There is a library in numpy that does exactly what we want to do:

https://numpy.org/doc/stable/reference/random/generated/numpy.random.dirichlet.html

`random.Generator.dirichlet(alpha, size=None)`

where,

`alpha = sequence of probabilities`

`size = size of the matrix` (in case we want output in a specific matrix shape rather then just a linear vector)