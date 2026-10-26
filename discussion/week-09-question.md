---
id: w09-mazy2005-kernel-selection-uncertainty
title: "Choosing Kernels When CV Errors Are Close"
author: "Zhiyuan Ma (mazy2005)"
---

Suppose a radial-kernel SVM has the lowest five-fold cross-validation error, but a linear SVM is only slightly worse. Both use the same folds, and predictors are standardized within each fitting fold. How should we decide whether the radial kernel's extra flexibility is justified? In particular, how does searching more combinations of cost and radial scale affect the credibility of the minimum validation error, and what evaluation procedure would let us select a kernel while still reporting a trustworthy estimate of prediction error?
