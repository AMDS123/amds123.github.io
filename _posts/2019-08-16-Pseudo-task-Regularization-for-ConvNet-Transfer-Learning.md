---
layout: post
title: "Pseudo-task Regularization for ConvNet Transfer Learning"
date: 2019-08-16 14:57:12
categories: arXiv_CV
tags: arXiv_CV Image_Caption Regularization CNN Transfer_Learning Classification
author: Yang Zhong, Atsuto Maki
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is about regularizing deep convolutional networks (ConvNets) based on an adaptive multi-objective framework for transfer learning with limited training data in the target domain. Recent advances of ConvNets regularization in this context are commonly due to the use of additional regularization objectives. They guide the training away from the target task using some concrete tasks. Unlike those related approaches, we report that an objective without a concrete goal can serve surprisingly well as a regularizer. In particular, we demonstrate Pseudo-task Regularization (PtR) which dynamically regularizes a network by simply attempting to regress image representations to a pseudo-target during fine-tuning. Through numerous experiments, the improvements on classification accuracy by PtR are shown greater or on a par to the recent state-of-the-art methods. These results also indicate a room for rethinking on the requirements for a regularizer, i.e., if specifically designed task for regularization is indeed a key ingredient. The contributions of this paper are: a) PtR provides an effective and efficient alternative for regularization without dependence on concrete tasks or extra data; b) desired strength of regularization effect in PtR is dynamically adjusted and maintained based on the gradient norms of the target objective and the pseudo-task.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05997](https://arxiv.org/abs/1908.05997)

##### PDF
[https://arxiv.org/pdf/1908.05997](https://arxiv.org/pdf/1908.05997)

