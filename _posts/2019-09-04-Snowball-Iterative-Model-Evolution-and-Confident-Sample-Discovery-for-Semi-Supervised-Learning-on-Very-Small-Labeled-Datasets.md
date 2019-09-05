---
layout: post
title: "Snowball: Iterative Model Evolution and Confident Sample Discovery for Semi-Supervised Learning on Very Small Labeled Datasets"
date: 2019-09-04 03:41:27
categories: arXiv_CV
tags: arXiv_CV Knowledge Prediction
author: Yang Li, Jianhe Yuan, Zhiqun Zhao, Hao Sun, Zhihai He
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we develop a joint sample discovery and iterative model evolution method for semi-supervised learning on very small labeled training sets. We propose a master-teacher-student model framework to provide multi-layer guidance during the model evolution process with multiple iterations and generations. The teacher model is constructed by performing an exponential moving average of the student models obtained from past training steps. The master network combines the knowledge of the student and teacher models with additional access to newly discovered samples. The master and teacher models are then used to guide the training of the student network by enforcing the consistence between their predictions of unlabeled samples and evolve all models when more and more samples are discovered. Our extensive experiments demonstrate that the discovering confident samples from the unlabeled dataset, once coupled with the above master-teacher-student network evolution, can significantly improve the overall semi-supervised learning performance. For example, on the CIFAR-10 dataset, with a very small set of 250 labeled samples, our method achieves an error rate of 11.81 %, more than 38 % lower than the state-of-the-art method Mean-Teacher (49.91 %).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01542](http://arxiv.org/abs/1909.01542)

##### PDF
[http://arxiv.org/pdf/1909.01542](http://arxiv.org/pdf/1909.01542)

