# SVR (Support vector regression)
* SVR uses kernels to model data
* kernel : mathematical functions to take input data and transform them into required one
    * multiple linear and non linear kernels can be found, most widely used one is RBF(radial basis function)
* A tube instead of a regression line is created , this tube has a height of epsilon(e) margin of error
    * pointoutside this margin of error range are called suppor vectors that supports the tube,
    * we tend to minimise the total distance of support vectors from the tube
