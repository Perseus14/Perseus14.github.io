---
layout: post
title: Linear Regression
---

In this article, I will attempt to explain Linear Regression, go through the intuition, the theory and write a python code from scratch using  numpy.

Wikipedia says
>  Llinear regression is a linear approach for modeling the relationship between a scalar dependent variable y and one or more explanatory variables (or independent variables) denoted X.

which basically means, given some points in a 2D space, if you can draw a line that passes through most of them, the n the relationships between the variables are linear in nature, the line can now predict for unknown values of variables.

Suppose you have a dataset of the form  
$x$, $y$  
where you want to predict values of  y for some previously unseen value of x.  

We first assume that the variables form some sort of linear relationship (i.e)  
>$$ y = m*x + c $$

Objective is to find $m$ and $c$ that can fit the dataset as closely as it can. "Closely" here means
the line should pass through as many points as it can. To calculate closeness we first calculate the error, (i.e) how far off is the line from the point which is given by the formula

> $$ _Error_  = abs(y' - y)^2 $$   
> $$ _Error_  = abs(y' -  (m*x' + c))^2  $$  

where $y'$ means the actual value  and $y$ the predicted value for some $x'$ . 

We want the line to be as close as possible this means error should be as low as possible.  
Lower the error, Closer the Line, Better the model !!



	
{% include lib/mathjax.html %}