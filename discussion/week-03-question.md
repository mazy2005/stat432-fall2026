---
id: w03-mazy2005-gcv-preprocessing
title: "Does GCV Account for Repeated Standardization?"
author: "Zhiyuan Ma (mazy2005)"
---

In ridge cross-validation, we recompute predictor means and scales within each training fold. In the homework's GCV calculation, however, we standardize once using the entire training set and use the resulting smoother's effective degrees of freedom. How should we interpret GCV as an approximation to leave-one-out cross-validation when leaving out an observation also changes the standardization? In particular, could an observation that strongly affects a predictor's scale cause the two procedures to favor substantially different penalties, even when both leave the intercept unpenalized?
