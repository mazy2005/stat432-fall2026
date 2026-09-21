---
id: w04-mazy2005-selection-prediction-stability
title: "Unstable Selection, Stable Prediction?"
author: "Zhiyuan Ma (mazy2005)"
---

Suppose two centered predictors have unit population variance and correlation $\rho$ close to one. Two training samples produce lasso fits with the same intercept but different selected variables: one predicts $cX_1$ and the other predicts $cX_2$, where $c$ is the same fixed coefficient. How can we use the expected squared difference between these predictions on a new observation to explain why unstable variable selection need not imply unstable prediction? In particular, what does this comparison tell us about interpreting the selected variable as uniquely important, and what does it leave unresolved about either model's prediction error for $Y$?
