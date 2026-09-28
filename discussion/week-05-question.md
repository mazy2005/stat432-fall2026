---
id: w05-mazy2005-redundant-knn-distances
title: "Redundant Predictors and KNN Distances"
author: "Zhiyuan Ma (mazy2005)"
---

Suppose a KNN regression model uses Euclidean distance on two standardized predictors, $X_1$ and $X_2$. We replace $X_1$ with $r$ identical copies, retain one copy of $X_2$, and standardize every column again using the same training observations. Although the copies add no predictive information, can they change which observations are nearest neighbors? Use the resulting squared distance to explain whether column standardization removes this effect and how the copied coordinates could be weighted to recover the original distances for every pair of observations.
