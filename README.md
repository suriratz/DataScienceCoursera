# DataScienceCoursera
Data Science Specialization
x <- 1:20

> x
 [1]  1  2  3  4  5  6  7  8  9 10

# modulo division
> x %% 2 == 0
 [1] FALSE  TRUE FALSE  TRUE FALSE  TRUE FALSE  TRUE FALSE  TRUE


is.even <- function(x) x %% 2 == 0

> is.even(x)
 [1] FALSE  TRUE FALSE  TRUE FALSE  TRUE FALSE  TRUE FALSE  TRUE


> is.odd <- function(x) x %% 2 != 0
