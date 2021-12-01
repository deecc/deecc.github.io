---
title: "Applied Statistics: Machine Learning Methods and Causal Inference in Economic Analysis "
excerpt: "These are the R and Python codes that I have developed in the course Applied Statistics: Machine Learning Methods and Causal Inference in Economic Analysis with my colleagues Sonia Asto and Nicole Linares."
collection: Codes
---
[The wage gap](https://github.com/deecc/AS/tree/main/The%20gender%20wage%20gap)  : In this script we seek to explain the wage gap between women and men by focusing on workers with some college vs. those who have finished college, based on the Mincer equation, which considers that wages are affected by certain characteristics such as experience, education, etc. The Frish-Waugh-Lovell theorem is also explained mathematically.


[Lasso model](https://github.com/deecc/AS/tree/main/Lasso-data%20splitting) : In this script we started working with an ols model to estimate the wage gap between women and men but focusing on workers with some college vs. those who finished college, later we incorporated a more complex model such as a flexible model in order to reduce the bias of the first model and thus obtain a better interpretation, however, this model has limitations when faced with few observations. To complement this analysis we incorporated a lasso model, which highlights the most important variables for the regression.


[RCT data with Precision Adjustment](https://github.com/deecc/AS/tree/main/RCT%20data%20with%20Precision%20Adjustment): In this script we begin by explaining the problems caused by multicollinearity. Subsequently, we work with the Pennsylvania re-employment bonus experiment, and compare it with different models that incorporate precision adjustment such as classical linear regression adjustment (CRA), interactive regression adjustment (IRA) and interactive regression adjustment (IRA) using Lasso, and we also work with the classical 2-sample approach no adjustment (CL) model, in order to compare and obtain the best model. 



[Orthogonal learning and double lasso](https://github.com/deecc/AS/tree/main/Orthogonal%20learning%20and%20double%20lasso): In this script we test the convergence hypothesis proposed by Barro-Lee. For this we used different models such as ols, double lasso with coss validation, double lasso with theorical lambda , double lasso with partialling out. The results were that the partialling-out model via Lasso provides a more accurate estimation. The point estimate based on the Double Lasso is -5% and the confidence interval of 95% for the (annual) convergence rate -7.75%,-2.21% includes only negative numbers. This empirical evidence supports the convergence hypothesis.




 [Causal Forest and Debiased Machine Learning](https://github.com/deecc/AS/tree/main/Causal%20Forest%20and%20Debiased%20Machine%20Learning): In this script we work with the deviased machine learning algorithm and incorporate it to different models such as ols, lasso, post- lasso, elastic net, lasso-ridge and random forst in order to test the convergence hypothesis proposed by Barro-Lee. We find that the best model for d(initial wealth) is cross validation elnet and for Y(growth rate) is cross validation lasso. 