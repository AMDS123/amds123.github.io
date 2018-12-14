---
layout: post
title: "When Semi-Supervised Learning Meets Transfer Learning: Training Strategies, Models and Datasets"
date: 2018-12-13 08:46:42
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning
author: Hong-Yu Zhou, Avital Oliver, Jianxin Wu, Yefeng Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Semi-Supervised Learning (SSL) has been proved to be an effective way to leverage both labeled and unlabeled data at the same time. Recent semi-supervised approaches focus on deep neural networks and have achieved promising results on several benchmarks: CIFAR10, CIFAR100 and SVHN. However, most of their experiments are based on models trained from scratch instead of pre-trained models. On the other hand, transfer learning has demonstrated its value when the target domain has limited labeled data. Here comes the intuitive question: is it possible to incorporate SSL when fine-tuning a pre-trained model? We comprehensively study how SSL methods starting from pretrained models perform under varying conditions, including training strategies, architecture choice and datasets. From this study, we obtain several interesting and useful observations. 
 While practitioners have had an intuitive understanding of these observations, we do a comprehensive emperical analysis and demonstrate that: (1) the gains from SSL techniques over a fully-supervised baseline are smaller when trained from a pre-trained model than when trained from random initialization, (2) when the domain of the source data used to train the pre-trained model differs significantly from the domain of the target task, the gains from SSL are significantly higher and (3) some SSL methods are able to advance fully-supervised baselines (like Pseudo-Label). 
 We hope our studies can deepen the understanding of SSL research and facilitate the process of developing more effective SSL methods to utilize pre-trained models. Code is now available at github.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05313](http://arxiv.org/abs/1812.05313)

##### PDF
[http://arxiv.org/pdf/1812.05313](http://arxiv.org/pdf/1812.05313)

