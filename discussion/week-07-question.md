---
id: w07-mazy2005-embeddings-class-information
title: "What Should an Embedding Preserve for LDA/QDA?"
author: "Zhiyuan Ma (mazy2005)"
---

How should we judge whether a low-dimensional embedding is useful before fitting LDA or QDA? PCA retains directions with high overall variance, while a random projection can approximately preserve pairwise distances. How do these goals relate to preserving the information that separates classes, including differences in their covariance matrices? Can an embedding make covariance estimates more stable yet worsen prediction by discarding a low-variance but informative direction? What diagnostics and cross-validation design would help us choose the embedding and its dimension without using the reserved test set?
