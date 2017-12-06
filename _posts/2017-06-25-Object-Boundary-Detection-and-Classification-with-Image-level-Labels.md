---
layout: post
title: "Object Boundary Detection and Classification with Image-level Labels"
date: 2017-06-25 12:50:55
categories: arXiv_CV
tags: arXiv_CV Detection
author: Jing Yu Koh, Wojciech Samek, Klaus-Robert Müller, Alexander Binder
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic boundary and edge detection aims at simultaneously detecting object edge pixels in images and assigning class labels to them. Systematic training of predictors for this task requires the labeling of edges in images which is a particularly tedious task. We propose a novel strategy for solving this task, when pixel-level annotations are not available, performing it in an almost zero-shot manner by relying on conventional whole image neural net classifiers that were trained using large bounding boxes. Our method performs the following two steps at test time. Firstly it predicts the class labels by applying the trained whole image network to the test images. Secondly, it computes pixel-wise scores from the obtained predictions by applying backprop gradients as well as recent visualization algorithms such as deconvolution and layer-wise relevance propagation. We show that high pixel-wise scores are indicative for the location of semantic boundaries, which suggests that the semantic boundary problem can be approached without using edge labels during the training phase.

##### Abstract (translated by Google)
语义边界和边缘检测的目的是同时检测图像中的物体边缘像素并为其分配类别标签。对这个任务进行系统预测的训练需要在图像中标出边缘，这是一项特别枯燥的任务。我们提出了一个新的解决这个任务的策略，当像素级注释不可用时，依靠传统的全图像神经网络分类器，使用大型包围盒进行训练，以几乎零射击的方式执行它。我们的方法在测试时执行以下两个步骤。首先通过将训练好的整个图像网络应用于测试图像来预测类别标签。其次，它通过应用反向梯度以及最近的可视化算法（例如去卷积和分层相关性传播）来从所获得的预测计算像素分数。我们表明，高像素的得分是指示语义边界的位置，这表明语义边界问题可以接近，而不使用边缘标签在训练阶段。

##### URL
[https://arxiv.org/abs/1606.09187](https://arxiv.org/abs/1606.09187)

