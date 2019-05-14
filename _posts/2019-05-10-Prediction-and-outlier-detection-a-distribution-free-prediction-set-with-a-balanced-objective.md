---
layout: post
title: "Prediction and outlier detection: a distribution-free prediction set with a balanced objective"
date: 2019-05-10 22:56:39
categories: arXiv_CV
tags: arXiv_CV Classification Prediction Detection
author: Leying Guan, Rob Tibshirani
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the multi-class classification problem when the training data and the out-of-sample test data may have different distributions and propose a method called BCOPS (balanced and conformal optimized prediction set) that constructs a prediction set C(x) which tries to optimize out-of-sample performance, aiming to include the correct class as often as possible, but also detecting outliers x, for which the method returns no prediction (corresponding to C(x) equal to the empty set). BCOPS combines supervised-learning algorithms with the method of conformal prediction to minimize a misclassification loss averaged over the out-of-sample distribution. The constructed prediction sets have a finite-sample coverage guarantee without distributional assumptions. We also develop a variant of BCOPS in the online setting where we optimize the misclassification loss averaged over a proxy of the out-of-sample distribution. We also describe new methods for the evaluation of out-of-sample performance with mismatched data. We prove asymptotic consistency and efficiency of the proposed methods under suitable assumptions and illustrate our methods on real data examples.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.04396](https://arxiv.org/abs/1905.04396)

##### PDF
[https://arxiv.org/pdf/1905.04396](https://arxiv.org/pdf/1905.04396)

