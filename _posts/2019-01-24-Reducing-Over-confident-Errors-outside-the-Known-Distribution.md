---
layout: post
title: "Reducing Over-confident Errors outside the Known Distribution"
date: 2019-01-24 15:41:03
categories: arXiv_CV
tags: arXiv_CV Face Prediction Detection Recognition
author: Zhizhong Li, Derek Hoiem
mathjax: true
---

* content
{:toc}

##### Abstract
Intuitively, unfamiliarity should lead to lack of confidence. In reality, current algorithms often make highly confident yet wrong predictions when faced with unexpected test samples from an unknown distribution different from training. Unlike domain adaptation methods, we cannot gather an "unexpected dataset" prior to test, and unlike novelty detection methods, a best-effort original task prediction is still expected. We compare a number of methods from related fields such as calibration and epistemic uncertainty modeling, as well as two proposed methods that reduce overconfident errors of samples from an unknown novel distribution without drastically increasing evaluation time: (1) G-distillation, training an ensemble of classifiers and then distill into a single model using both labeled and unlabeled examples, or (2) NCR, reducing prediction confidence based on its novelty detection score. Experimentally, we investigate the overconfidence problem and evaluate our solution by creating "familiar" and "novel" test splits, where "familiar" are identically distributed with training and "novel" are not. We discover that calibrating using temperature scaling on familiar data is the best single-model method for improving novel confidence, followed by our proposed methods. In addition, some methods' NLL performance are roughly equivalent to a regularly trained model with certain degree of smoothing. Calibrating can also reduce confident errors, for example, in gender recognition by 95\% on demographic groups different from the training data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.03166](http://arxiv.org/abs/1804.03166)

##### PDF
[http://arxiv.org/pdf/1804.03166](http://arxiv.org/pdf/1804.03166)

