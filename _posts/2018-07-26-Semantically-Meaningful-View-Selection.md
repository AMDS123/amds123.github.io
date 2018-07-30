---
layout: post
title: "Semantically Meaningful View Selection"
date: 2018-07-26 18:17:19
categories: arXiv_RO
tags: arXiv_RO Image_Caption Knowledge Deep_Learning Recognition
author: Joris Guérin, Olivier Gibaru, Eric Nyiri, Stéphane Thiery, Byron Boots
mathjax: true
---

* content
{:toc}

##### Abstract
An understanding of the nature of objects could help robots to solve both high-level abstract tasks and improve performance at lower-level concrete tasks. Although deep learning has facilitated progress in image understanding, a robot's performance in problems like object recognition often depends on the angle from which the object is observed. Traditionally, robot sorting tasks rely on a fixed top-down view of an object. By changing its viewing angle, a robot can select a more semantically informative view leading to better performance for object recognition. In this paper, we introduce the problem of semantic view selection, which seeks to find good camera poses to gain semantic knowledge about an observed object. We propose a conceptual formulation of the problem, together with a solvable relaxation based on clustering. We then present a new image dataset consisting of around 10k images representing various views of 144 objects under different poses. Finally we use this dataset to propose a first solution to the problem by training a neural network to predict a "semantic score" from a top view image and camera pose. The views predicted to have higher scores are then shown to provide better clustering results than fixed top-down views.

##### Abstract (translated by Google)
了解对象的本质可以帮助机器人解决高级抽象任务并提高低级别具体任务的性能。尽管深度学习促进了图像理解的进步，但是机器人在物体识别等问题中的表现通常取决于观察物体的角度。传统上，机器人分类任务依赖于对象的固定自顶向下视图。通过改变其视角，机器人可以选择更具语义信息的视图，从而获得更好的对象识别性能。在本文中，我们介绍了语义视图选择的问题，该问题旨在找到良好的相机姿势以获得关于被观察对象的语义知识。我们提出了问题的概念表达式，以及基于聚类的可解决的放松。然后，我们提出了一个新的图像数据集，其中包含大约10k个图像，这些图像代表不同姿势下144个对象最后，我们使用该数据集通过训练神经网络从顶视图图像和相机姿势预测“语义分数”来提出问题的第一解决方案。然后显示预测具有更高分数的视图提供比固定自上而下视图更好的聚类结果。

##### URL
[https://arxiv.org/abs/1807.10303](https://arxiv.org/abs/1807.10303)

##### PDF
[https://arxiv.org/pdf/1807.10303](https://arxiv.org/pdf/1807.10303)

