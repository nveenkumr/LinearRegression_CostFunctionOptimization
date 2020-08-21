# LinearRegression Cost Funciton Optimization 

## Why Cost Function 
In Linear Regression we generally try to find out the best fit linne , As we know linear regression y = mx +c and to have the best fit line we should have optimal m and c value. 
So Cost function helps us to reach the optimal solution 

e.g. Cost function here is Residual sum of square (RSS) and our goal is to minimize this error
  J(θ0,θ1) = ∑(i=1 to N)(yi-yi_Pred)**2

  Where y, is original point and yi_Pred is predicted value.
  
## Techniques 
  There are 2 optimization techniques to minimize the the cost function
  1. Closed form  2. Iterative Form 
  
#### 1. Clsoed Form  :- 
   a. Here we simply differentiate the cost function and equate to Zero 
      
#### 2. Iterative Form :-  
    b. Gradient descent is an iterative method of optimising an objective function, in our case the cost function, by moving toward the negative of the gradient.
    
    Please see the attached jupyter notebook for detailed implementation of both the approaches
