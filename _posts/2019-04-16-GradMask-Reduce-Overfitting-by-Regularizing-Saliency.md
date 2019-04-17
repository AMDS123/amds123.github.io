---
layout: post
title: "GradMask: Reduce Overfitting by Regularizing Saliency"
date: 2019-04-16 05:57:50
categories: arXiv_CV
tags: arXiv_CV Regularization Salient Segmentation Classification Prediction
author: Becks Simpson, Francis Dutil, Yoshua Bengio, Joseph Paul Cohen
mathjax: true
---

* content
{:toc}

##### Abstract
With too few samples or too many model parameters, overfitting can inhibit the ability to generalise predictions to new data. Within medical imaging, this can occur when features are incorrectly assigned importance such as distinct hospital specific artifacts, leading to poor performance on a new dataset from a different institution without those features, which is undesirable. Most regularization methods do not explicitly penalize the incorrect association of these features to the target class and hence fail to address this issue. We propose a regularization method, GradMask, which penalizes saliency maps inferred from the classifier gradients when they are not consistent with the lesion segmentation. This prevents non-tumor related features to contribute to the classification of unhealthy samples. We demonstrate that this method can improve test accuracy between 1-3% compared to the baseline without GradMask, showing that it has an impact on reducing overfitting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07478](http://arxiv.org/abs/1904.07478)

##### PDF
[http://arxiv.org/pdf/1904.07478](http://arxiv.org/pdf/1904.07478)

