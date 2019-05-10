---
layout: post
title: "SOSELETO: A Unified Approach to Transfer Learning and Training with Noisy Labels"
date: 2019-05-09 15:41:44
categories: arXiv_AI
tags: arXiv_AI Regularization Transfer_Learning Optimization Classification
author: Or Litany, Daniel Freedman
mathjax: true
---

* content
{:toc}

##### Abstract
We present SOSELETO (SOurce SELEction for Target Optimization), a new method for exploiting a source dataset to solve a classification problem on a target dataset. SOSELETO is based on the following simple intuition: some source examples are more informative than others for the target problem. To capture this intuition, source samples are each given weights; these weights are solved for jointly with the source and target classification problems via a bilevel optimization scheme. The target therefore gets to choose the source samples which are most informative for its own classification task. Furthermore, the bilevel nature of the optimization acts as a kind of regularization on the target, mitigating overfitting. SOSELETO may be applied to both classic transfer learning, as well as the problem of training on datasets with noisy labels; we show state of the art results on both of these problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.09622](http://arxiv.org/abs/1805.09622)

##### PDF
[http://arxiv.org/pdf/1805.09622](http://arxiv.org/pdf/1805.09622)

