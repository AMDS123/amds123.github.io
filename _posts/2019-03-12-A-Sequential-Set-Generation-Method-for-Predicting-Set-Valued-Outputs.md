---
layout: post
title: "A Sequential Set Generation Method for Predicting Set-Valued Outputs"
date: 2019-03-12 19:06:18
categories: arXiv_AI
tags: arXiv_AI Regularization Classification Prediction
author: Tian Gao, Jie Chen, Vijil Chenthamarakshan, Michael Witbrock
mathjax: true
---

* content
{:toc}

##### Abstract
Consider a general machine learning setting where the output is a set of labels or sequences. This output set is unordered and its size varies with the input. Whereas multi-label classification methods seem a natural first resort, they are not readily applicable to set-valued outputs because of the growth rate of the output space; and because conventional sequence generation doesn't reflect sets' order-free nature. In this paper, we propose a unified framework--sequential set generation (SSG)--that can handle output sets of labels and sequences. SSG is a meta-algorithm that leverages any probabilistic learning method for label or sequence prediction, but employs a proper regularization such that a new label or sequence is generated repeatedly until the full set is produced. Though SSG is sequential in nature, it does not penalize the ordering of the appearance of the set elements and can be applied to a variety of set output problems, such as a set of classification labels or sequences. We perform experiments with both benchmark and synthetic data sets and demonstrate SSG's strong performance over baseline methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05153](http://arxiv.org/abs/1903.05153)

##### PDF
[http://arxiv.org/pdf/1903.05153](http://arxiv.org/pdf/1903.05153)

