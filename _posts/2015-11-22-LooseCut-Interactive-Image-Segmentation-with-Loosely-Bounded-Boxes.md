---
layout: post
title: "LooseCut: Interactive Image Segmentation with Loosely Bounded Boxes"
date: 2015-11-22 03:54:17
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Detection
author: Hongkai Yu, Youjie Zhou, Hui Qian, Min Xian, Yuewei Lin, Dazhou Guo, Kang Zheng, Kareem Abdelfatah, Song Wang
mathjax: true
---

* content
{:toc}

##### Abstract
One popular approach to interactively segment the foreground object of interest from an image is to annotate a bounding box that covers the foreground object. Then, a binary labeling is performed to achieve a refined segmentation. One major issue of the existing algorithms for such interactive image segmentation is their preference of an input bounding box that tightly encloses the foreground object. This increases the annotation burden, and prevents these algorithms from utilizing automatically detected bounding boxes. In this paper, we develop a new LooseCut algorithm that can handle cases where the input bounding box only loosely covers the foreground object. We propose a new Markov Random Fields (MRF) model for segmentation with loosely bounded boxes, including a global similarity constraint to better distinguish the foreground and background, and an additional energy term to encourage consistent labeling of similar-appearance pixels. This MRF model is then solved by an iterated max-flow algorithm. In the experiments, we evaluate LooseCut in three publicly-available image datasets, and compare its performance against several state-of-the-art interactive image segmentation algorithms. We also show that LooseCut can be used for enhancing the performance of unsupervised video segmentation and image saliency detection.

##### Abstract (translated by Google)
从图像中交互地分割感兴趣的前景对象的一种流行的方法是注释覆盖前景对象的边界框。然后，执行二元标记以实现精细分割。对于这种交互式图像分割的现有算法的一个主要问题是它们偏好紧密包围前景对象的输入边界框。这增加了注释的负担，并且阻止这些算法利用自动检测的边界框。在本文中，我们开发了一种新的LooseCut算法，可以处理输入边界框只松散地覆盖前景对象的情况。我们提出了一个新的马尔可夫随机场（MRF）模型用于松散有界框的分割，包括一个全局相似性约束，以更好地区分前景和背景，以及一个额外的能量项，以鼓励类似外观像素的一致标记。然后通过迭代的最大流算法来解决这个MRF模型。在实验中，我们评估了三种公开可用的图像数据集中的LooseCut，并将其性能与几种最先进的交互式图像分割算法进行比较。我们还展示了LooseCut可以用来提高无监督视频分割和图像显着性检测的性能。

##### URL
[https://arxiv.org/abs/1507.03060](https://arxiv.org/abs/1507.03060)

##### PDF
[https://arxiv.org/pdf/1507.03060](https://arxiv.org/pdf/1507.03060)

