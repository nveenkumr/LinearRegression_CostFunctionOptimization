# LinearRegression Cost Funciton Optimization 

## Why Cost Function 
In Linear Regression we generally try to find out the best fit line , As we know linear regression equation y = mx +c and to have the best fit line we should have optimal m and c value. 
So Cost function helps us to reach the optimal solution 

e.g. Cost function here is Residual sum of square (RSS) and our goal is to minimize this error.

  J(θ0,θ1) = ∑(i=1 to N)(yi-yi_Pred)**2

  Where θ0,θ1 are coefficient values i.e. m and c , y is original point and yi_Pred is predicted value.
  
## Techniques 
  There are 2 optimization techniques to minimize the the cost function
  1. Closed form  2. Iterative Form 
  
#### 1. Clsoed Form  :- 
   a. Here we simply differentiate the cost function and equate to Zero 
      
#### 2. Iterative Form :-


   b. Gradient descent is an iterative method of optimising an objective function, in our case the cost function, by moving toward the negative of the gradient.
      
      To compute θ1, equation will look like this,
      θ1= θ0−η ∂/∂θ (J(θ))
      Where η (Eta) is known as the learning rate, which defines the speed at which we want to move towards negative of the gradient.
 
Please see the attached jupyter notebook for detailed implementation of both the approaches
