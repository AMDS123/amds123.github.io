---
layout: post
title: "Direction-aware Spatial Context Features for Shadow Detection and Removal"
date: 2019-05-25 05:38:18
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Detection
author: Xiaowei Hu, Chi-Wing Fu, Lei Zhu, Jing Qin, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Shadow detection and shadow removal are fundamental and challenging tasks, requiring an understanding of the global image semantics. This paper presents a novel deep neural network design for shadow detection and removal by analyzing the spatial image context in a direction-aware manner. To achieve this, we first formulate the direction-aware attention mechanism in a spatial recurrent neural network (RNN) by introducing attention weights when aggregating spatial context features in the RNN. By learning these weights through training, we can recover direction-aware spatial context (DSC) for detecting and removing shadows. This design is developed into the DSC module and embedded in a convolutional neural network (CNN) to learn the DSC features at different levels. Moreover, we design a weighted cross entropy loss to make effective the training for shadow detection and further adopt the network for shadow removal by using a Euclidean loss function and formulating a color transfer function to address the color and luminosity inconsistencies in the training pairs. We employed two shadow detection benchmark datasets and two shadow removal benchmark datasets, and performed various experiments to evaluate our method. Experimental results show that our method performs favorably against the state-of-the-art methods for both shadow detection and shadow removal.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.04635](http://arxiv.org/abs/1805.04635)

##### PDF
[http://arxiv.org/pdf/1805.04635](http://arxiv.org/pdf/1805.04635)

