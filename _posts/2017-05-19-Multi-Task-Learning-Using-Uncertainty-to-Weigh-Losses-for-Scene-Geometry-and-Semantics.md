---
layout: post
title: "Multi-Task Learning Using Uncertainty to Weigh Losses for Scene Geometry and Semantics"
date: 2017-05-19 17:56:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Deep_Learning
author: Alex Kendall, Yarin Gal, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
Numerous deep learning applications benefit from multi-task learning with multiple regression and classification objectives. In this paper we make the observation that the performance of such systems is strongly dependent on the relative weighting between each task's loss. Tuning these weights by hand is a difficult and expensive process, making multi-task learning prohibitive in practice. We propose a principled approach to multi-task deep learning which weighs multiple loss functions by considering the homoscedastic uncertainty of each task. This allows us to simultaneously learn various quantities with different units or scales in both classification and regression settings. We demonstrate our model learning per-pixel depth regression, semantic and instance segmentation from a monocular input image. Perhaps surprisingly, we show our model can learn multi-task weightings and outperform separate models trained individually on each task.

##### Abstract (translated by Google)
多种深度学习应用程序受益于具有多重回归和分类目标的多任务学习。在本文中，我们观察到这样的系统的性能强烈依赖于每个任务的损失之间的相对权重。用手调整这些权重是一个困难和昂贵的过程，使得多任务学习在实践中被禁止。我们提出了一个多任务深度学习的原则方法，通过考虑每个任务的同方差不确定性来权衡多个损失函数。这使我们可以在分类和回归设置中同时学习不同单位或尺度的各种数量。我们演示了我们的模型学习单像素输入图像的每像素深度回归，语义和实例分割。也许令人惊讶的是，我们展示了我们的模型可以学习多任务权重，并且胜过在每个任务上单独训练的单独模型。

##### URL
[https://arxiv.org/abs/1705.07115](https://arxiv.org/abs/1705.07115)

##### PDF
[https://arxiv.org/pdf/1705.07115](https://arxiv.org/pdf/1705.07115)

