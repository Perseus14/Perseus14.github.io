---
layout: post
title: Linear Regression
---

In this article, I will attempt to explain Linear Regression, go through the intuition, the theory and write a python code from scratch using  numpy.

Wikipedia says
>  Llinear regression is a linear approach for modeling the relationship between a scalar dependent variable y and one or more explanatory variables (or independent variables) denoted X.

which basically means, given some points in a 2D space, if you can draw a line that passes through most of them, the n the relationships between the variables are linear in nature, the line can now predict for unknown values of variables.

Suppose you have a dataset of the form  
 x,  y  
where you want to predict values of  y for some previously unseen value of x.  

We first assume that the variables form some sort of linear relationship (i.e)  
	$$ y = m*x + c $$

{% include lib/mathjax.html %}
