---
layout: post
title: "A Domain Guided CNN Architecture for Predicting Age from Structural Brain Images"
date: 2018-08-11 19:43:22
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Recognition
author: Pascal Sturmfels, Saige Rutherford, Mike Angstadt, Mark Peterson, Chandra Sripada, Jenna Wiens
mathjax: true
---

* content
{:toc}

##### Abstract
Given the wide success of convolutional neural networks (CNNs) applied to natural images, researchers have begun to apply them to neuroimaging data. To date, however, exploration of novel CNN architectures tailored to neuroimaging data has been limited. Several recent works fail to leverage the 3D structure of the brain, instead treating the brain as a set of independent 2D slices. Approaches that do utilize 3D convolutions rely on architectures developed for object recognition tasks in natural 2D images. Such architectures make assumptions about the input that may not hold for neuroimaging. For example, existing architectures assume that patterns in the brain exhibit translation invariance. However, a pattern in the brain may have different meaning depending on where in the brain it is located. There is a need to explore novel architectures that are tailored to brain images. We present two simple modifications to existing CNN architectures based on brain image structure. Applied to the task of brain age prediction, our network achieves a mean absolute error (MAE) of 1.4 years and trains 30% faster than a CNN baseline that achieves a MAE of 1.6 years. Our results suggest that lessons learned from developing models on natural images may not directly transfer to neuroimaging tasks. Instead, there remains a large space of unexplored questions regarding model development in this area, whose answers may differ from conventional wisdom.

##### Abstract (translated by Google)
鉴于卷积神经网络（CNN）应用于自然图像的广泛成功，研究人员已开始将它们应用于神经成像数据。然而，迄今为止，针对神经成像数据定制的新型CNN架构的探索受到限制。最近的一些作品未能利用大脑的3D结构，而是将大脑视为一组独立的2D切片。确实利用3D卷积的方法依赖于为自然2D图像中的对象识别任务开发的架构。这种架构假设输入可能不适用于神经成像。例如，现有架构假设大脑中的模式表现出平移不变性。然而，大脑中的模式可能具有不同的含义，这取决于它所处的大脑中的位置。需要探索针对脑图像定制的新颖架构。我们基于脑图像结构对现有的CNN架构进行了两种简单的修改。应用于脑年龄预测的任务，我们的网络实现了1。4年的平均绝对误差（MAE），并且比实现1。6年MAE的CNN基线快30％。我们的研究结果表明，从自然图像开发模型中获得的经验可能不会直接转移到神经影像学任务。相反，在这个领域仍然存在大量关于模型发展的未开发问题，其答案可能与传统智慧不同。

##### URL
[http://arxiv.org/abs/1808.04362](http://arxiv.org/abs/1808.04362)

##### PDF
[http://arxiv.org/pdf/1808.04362](http://arxiv.org/pdf/1808.04362)

