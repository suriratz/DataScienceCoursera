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
#######

### prime number##
prime <- function(x){
for(i in 1:100)
if(x==1){print("TRUE")}
if((x %% (1:x-1))==0){print("TRUE")}
else{print("FALSE")}


print(seq(as.numeric("TRUE")))
Any help will be appr
