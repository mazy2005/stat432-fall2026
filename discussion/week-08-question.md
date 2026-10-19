---
id: w08-mazy2005-svm-feature-scaling
title: "Feature Scaling, Margins, and SVM Cost"
author: "Zhiyuan Ma (mazy2005)"
---

For a linear soft-margin SVM minimizing $\frac12\|\boldsymbol{\beta}\|_2^2+C\sum_i\xi_i$, with cost $C>0$ and slack variables $\xi_i$, how does the predictor representation affect the idea of a wide margin? If we rescale one predictor by a nonzero constant or replace it with several identical copies, can the fitted boundary and support vectors change even though the information is unchanged? Can retuning a single $C$ always compensate, or does this change the relative penalty on different coefficient directions? What preprocessing and cross-validation steps should an SVM analysis skill require for a fair comparison?
