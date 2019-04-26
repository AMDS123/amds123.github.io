---
layout: post
title: "Transferrable Prototypical Networks for Unsupervised Domain Adaptation"
date: 2019-04-25 09:21:16
categories: arXiv_CV
tags: arXiv_CV Embedding Optimization Classification
author: Yingwei Pan, Ting Yao, Yehao Li, Yu Wang, Chong-Wah Ngo, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a new idea for unsupervised domain adaptation via a remold of Prototypical Networks, which learn an embedding space and perform classification via a remold of the distances to the prototype of each class. Specifically, we present Transferrable Prototypical Networks (TPN) for adaptation such that the prototypes for each class in source and target domains are close in the embedding space and the score distributions predicted by prototypes separately on source and target data are similar. Technically, TPN initially matches each target example to the nearest prototype in the source domain and assigns an example a "pseudo" label. The prototype of each class could then be computed on source-only, target-only and source-target data, respectively. The optimization of TPN is end-to-end trained by jointly minimizing the distance across the prototypes on three types of data and KL-divergence of score distributions output by each pair of the prototypes. Extensive experiments are conducted on the transfers across MNIST, USPS and SVHN datasets, and superior results are reported when comparing to state-of-the-art approaches. More remarkably, we obtain an accuracy of 80.4% of single model on VisDA 2017 dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11227](http://arxiv.org/abs/1904.11227)

##### PDF
[http://arxiv.org/pdf/1904.11227](http://arxiv.org/pdf/1904.11227)

