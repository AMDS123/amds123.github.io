---
layout: post
title: "Network Implosion: Effective Model Compression for ResNets via Static Layer Pruning and Retraining"
date: 2019-06-10 07:53:18
categories: arXiv_AI
tags: arXiv_AI CNN Classification
author: Yasutoshi Ida, Yasuhiro Fujiwara
mathjax: true
---

* content
{:toc}

##### Abstract
Residual Networks with convolutional layers are widely used in the field of machine learning. Since they effectively extract features from input data by stacking multiple layers, they can achieve high accuracy in many applications. However, the stacking of many layers raises their computation costs. To address this problem, we propose Network Implosion, it erases multiple layers from Residual Networks without degrading accuracy. Our key idea is to introduce a priority term that identifies the importance of a layer; we can select unimportant layers according to the priority and erase them after the training. In addition, we retrain the networks to avoid critical drops in accuracy after layer erasure. A theoretical assessment reveals that our erasure and retraining scheme can erase layers without accuracy drop, and achieve higher accuracy than is possible with training from scratch. Our experiments show that Network Implosion can, for classification on Cifar-10/100 and ImageNet, reduce the number of layers by 24.00 to 42.86 percent without any drop in accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03826](http://arxiv.org/abs/1906.03826)

##### PDF
[http://arxiv.org/pdf/1906.03826](http://arxiv.org/pdf/1906.03826)

