---
layout: post
title: "A Holistic Approach for Data-Driven Object Cutout"
date: 2016-09-16 13:00:21
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Huayong Xu, Yangyan Li, Wenzheng Chen, Dani Lischinski, Daniel Cohen-Or, Baoquan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Object cutout is a fundamental operation for image editing and manipulation, yet it is extremely challenging to automate it in real-world images, which typically contain considerable background clutter. In contrast to existing cutout methods, which are based mainly on low-level image analysis, we propose a more holistic approach, which considers the entire shape of the object of interest by leveraging higher-level image analysis and learnt global shape priors. Specifically, we leverage a deep neural network (DNN) trained for objects of a particular class (chairs) for realizing this mechanism. Given a rectangular image region, the DNN outputs a probability map (P-map) that indicates for each pixel inside the rectangle how likely it is to be contained inside an object from the class of interest. We show that the resulting P-maps may be used to evaluate how likely a rectangle proposal is to contain an instance of the class, and further process good proposals to produce an accurate object cutout mask. This amounts to an automatic end-to-end pipeline for catergory-specific object cutout. We evaluate our approach on segmentation benchmark datasets, and show that it significantly outperforms the state-of-the-art on them.

##### Abstract (translated by Google)
对象剪切是图像编辑和操作的基本操作，但是在真实世界的图像中进行自动化非常具有挑战性，这些图像通常包含大量的背景杂乱。与现有的基于低级图像分析的剪切方法相比，我们提出了一种更全面的方法，通过利用更高级别的图像分析和学习的全局形状先验来考虑整个感兴趣对象的形状。具体而言，我们利用深度神经网络（DNN）为特定类别（椅子）的对象进行训练，以实现此机制。给定一个矩形图像区域，DNN输出一个概率图（P-map），指示矩形内的每个像素在感兴趣的类中包含在一个对象内的可能性。我们展示了生成的P-maps可能被用来评估一个矩形提案包含一个类的实例的可能性，并且进一步处理好的提议来产生一个精确的对象遮罩。这相当于一个自动的端到端管道，用于特定目标对象的切割。我们评估了我们在分割基准数据集上的方法，并显示它明显优于最新的分割基准数据集。

##### URL
[https://arxiv.org/abs/1608.05180](https://arxiv.org/abs/1608.05180)

##### PDF
[https://arxiv.org/pdf/1608.05180](https://arxiv.org/pdf/1608.05180)

