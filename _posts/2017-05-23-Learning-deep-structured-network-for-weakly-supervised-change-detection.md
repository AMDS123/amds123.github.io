---
layout: post
title: "Learning deep structured network for weakly supervised change detection"
date: 2017-05-23 01:22:06
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised Detection
author: Salman H Khan, Xuming He, Fatih Porikli, Mohammed Bennamoun, Ferdous Sohel, Roberto Togneri
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional change detection methods require a large number of images to learn background models or depend on tedious pixel-level labeling by humans. In this paper, we present a weakly supervised approach that needs only image-level labels to simultaneously detect and localize changes in a pair of images. To this end, we employ a deep neural network with DAG topology to learn patterns of change from image-level labeled training data. On top of the initial CNN activations, we define a CRF model to incorporate the local differences and context with the dense connections between individual pixels. We apply a constrained mean-field algorithm to estimate the pixel-level labels, and use the estimated labels to update the parameters of the CNN in an iterative EM framework. This enables imposing global constraints on the observed foreground probability mass function. Our evaluations on four benchmark datasets demonstrate superior detection and localization performance.

##### Abstract (translated by Google)
常规的变化检测方法需要大量的图像来学习背景模型或依赖于人类繁琐的像素级标记。在本文中，我们提出了一个弱监督的方法，只需要图像级别的标签来同时检测和定位一对图像的变化。为此，我们采用DAG拓扑的深度神经网络来从图像级标记的训练数据中学习变化的模式。在最初的CNN激活之上，我们定义了CRF模型，将局部差异和上下文与各个像素之间的密集连接相结合。我们应用约束平均场算法来估计像素级标签，并使用估计的标签在迭代EM框架中更新CNN的参数。这使得对观察到的前景概率质量函数施加全局约束。我们对四个基准数据集的评估表现出卓越的检测和本地化性能。

##### URL
[https://arxiv.org/abs/1606.02009](https://arxiv.org/abs/1606.02009)

##### PDF
[https://arxiv.org/pdf/1606.02009](https://arxiv.org/pdf/1606.02009)

