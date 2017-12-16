---
layout: post
title: "Learning to segment on tiny datasets: a new shape model"
date: 2017-08-07 15:26:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Maxime Tremblay, André Zaccarin
mathjax: true
---

* content
{:toc}

##### Abstract
Current object segmentation algorithms are based on the hypothesis that one has access to a very large amount of data. In this paper, we aim to segment objects using only tiny datasets. To this extent, we propose a new automatic part-based object segmentation algorithm for non-deformable and semi-deformable objects in natural backgrounds. We have developed a novel shape descriptor which models the local boundaries of an object's part. This shape descriptor is used in a bag-of-words approach for object detection. Once the detection process is performed, we use the background and foreground likelihood given by our trained shape model, and the information from the image content, to define a dense CRF model. We use a mean field approximation to solve it and thus segment the object of interest. Performance evaluated on different datasets shows that our approach can sometimes achieve results near state-of-the-art techniques based on big data while requiring only a tiny training set.

##### Abstract (translated by Google)
目前的对象分割算法是基于这样的假设，即人们可以访问非常大量的数据。在本文中，我们的目标是仅使用小数据集来分割对象。在这个意义上，我们提出了一种自然背景下的非变形和半变形物体自动分割的新方法。我们已经开发了一种新颖的形状描述符来模拟物体的局部边界。这种形状描述符用于对象检测的袋装词方法。一旦检测过程被执行，我们使用由我们训练的形状模型给出的背景和前景可能性，以及来自图像内容的信息来定义密集的CRF模型。我们使用平均场近似来解决它，从而分割感兴趣的对象。在不同数据集上评估的性能表明，我们的方法有时可以在基于大数据的最先进技术附近获得结果，而只需要很小的训练集。

##### URL
[https://arxiv.org/abs/1708.02165](https://arxiv.org/abs/1708.02165)

##### PDF
[https://arxiv.org/pdf/1708.02165](https://arxiv.org/pdf/1708.02165)

