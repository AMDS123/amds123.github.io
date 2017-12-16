---
layout: post
title: "Curriculum Domain Adaptation for Semantic Segmentation of Urban Scenes"
date: 2017-08-05 05:01:47
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction Relation
author: Yang Zhang, Philip David, Boqing Gong
mathjax: true
---

* content
{:toc}

##### Abstract
During the last half decade, convolutional neural networks (CNNs) have triumphed over semantic segmentation, which is a core task of various emerging industrial applications such as autonomous driving and medical imaging. However, to train CNNs requires a huge amount of data, which is difficult to collect and laborious to annotate. Recent advances in computer graphics make it possible to train CNN models on photo-realistic synthetic data with computer-generated annotations. Despite this, the domain mismatch between the real images and the synthetic data significantly decreases the models' performance. Hence we propose a curriculum-style learning approach to minimize the domain gap in semantic segmentation. The curriculum domain adaptation solves easy tasks first in order to infer some necessary properties about the target domain; in particular, the first task is to learn global label distributions over images and local distributions over landmark superpixels. These are easy to estimate because images of urban traffic scenes have strong idiosyncrasies (e.g., the size and spatial relations of buildings, streets, cars, etc.). We then train the segmentation network in such a way that the network predictions in the target domain follow those inferred properties. In experiments, our method significantly outperforms the baselines as well as the only known existing approach to the same problem.

##### Abstract (translated by Google)
在过去的五年中，卷积神经网络（CNNs）已经胜过了语义分割，这是各种新兴工业应用（如自动驾驶和医学成像）的核心任务。但是，培训CNN需要大量的数据，难以收集，费力注解。计算机图形学的最新进展使得利用计算机生成的注释来训练照片拟真合成数据上的CNN模型成为可能。尽管如此，真实图像和合成数据之间的域不匹配显着降低了模型的性能。因此，我们提出了一个课程式的学习方法，以尽量减少语义分割领域的差距。课程领域适应首先解决简单的任务，以推断有关目标领域的一些必要的属性;特别是第一项任务是学习标志性超像素的图像和本地分布的全局标签分布。因为城市交通场景的图像具有强烈的特性（例如，建筑物，街道，汽车等的大小和空间关系），所以这很容易估计。然后，我们训练分割网络，使得目标域中的网络预测遵循那些推断的属性。在实验中，我们的方法明显优于基线以及同样问题的唯一已知方法。

##### URL
[https://arxiv.org/abs/1707.09465](https://arxiv.org/abs/1707.09465)

##### PDF
[https://arxiv.org/pdf/1707.09465](https://arxiv.org/pdf/1707.09465)

