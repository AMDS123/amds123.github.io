---
layout: post
title: "Adaptive Ensemble Prediction for Deep Neural Networks based on Confidence Level"
date: 2019-03-08 11:46:51
categories: arXiv_CV
tags: arXiv_CV Inference Prediction Relation
author: Hiroshi Inoue
mathjax: true
---

* content
{:toc}

##### Abstract
Ensembling multiple predictions is a widely used technique for improving the accuracy of various machine learning tasks. One obvious drawback of ensembling is its higher execution cost during inference. In this paper, we first describe our insights on the relationship between the probability of prediction and the effect of ensembling with current deep neural networks; ensembling does not help mispredictions for inputs predicted with a high probability even when there is a non-negligible number of mispredicted inputs. This finding motivated us to develop a way to adaptively control the ensembling. If the prediction for an input reaches a high enough probability, i.e., the output from the softmax function, on the basis of the confidence level, we stop ensembling for this input to avoid wasting computation power. We evaluated the adaptive ensembling by using various datasets and showed that it reduces the computation cost significantly while achieving accuracy similar to that of static ensembling using a pre-defined number of local predictions. We also show that our statistically rigorous confidence-level-based early-exit condition reduces the burden of task-dependent threshold tuning better compared with naive early exit based on a pre-defined threshold in addition to yielding a better accuracy with the same cost.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1702.08259](http://arxiv.org/abs/1702.08259)

##### PDF
[http://arxiv.org/pdf/1702.08259](http://arxiv.org/pdf/1702.08259)

