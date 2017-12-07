---
layout: post
title: "Weakly Supervised Top-down Salient Object Detection"
date: 2016-11-17 02:24:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Tracking Detection
author: Hisham Cholakkal, Jubin Johnson, Deepu Rajan
mathjax: true
---

* content
{:toc}

##### Abstract
Top-down saliency models produce a probability map that peaks at target locations specified by a task/goal such as object detection. They are usually trained in a fully supervised setting involving pixel-level annotations of objects. We propose a weakly supervised top-down saliency framework using only binary labels that indicate the presence/absence of an object in an image. First, the probabilistic contribution of each image region to the confidence of a CNN-based image classifier is computed through a backtracking strategy to produce top-down saliency. From a set of saliency maps of an image produced by fast bottom-up saliency approaches, we select the best saliency map suitable for the top-down task. The selected bottom-up saliency map is combined with the top-down saliency map. Features having high combined saliency are used to train a linear SVM classifier to estimate feature saliency. This is integrated with combined saliency and further refined through a multi-scale superpixel-averaging of saliency map. We evaluate the performance of the proposed weakly supervised top-down saliency against fully supervised approaches and achieve state-of-the-art performance. Experiments are carried out on seven challenging datasets and quantitative results are compared with 36 closely related approaches across 4 different applications.

##### Abstract (translated by Google)
自上而下的显着性模型会生成一个概率图，在目标位置达到峰值，这些目标位置由任务/目标（如对象检测）指定。他们通常受到完全监督的设置的训练，涉及对象的像素级注释。我们提出一个弱监督的自顶向下的显着性框架，只使用二进制标签来指示图像中是否存在对象。首先，通过回溯策略计算每个图像区域对基于CNN的图像分类器的置信度的概率贡献，以产生自顶向下的显着性。从快速自下而上显着方法产生的一组图像的显着性图，我们选择适合自上而下任务的最佳显着性图。所选的自下而上的显着图与自顶向下的显着图组合。使用具有高组合显着性的特征来训练线性SVM分类器来估计特征显着性。这与综合显着性相结合，并通过显着图的多尺度超像素平均进一步细化。我们评估所提出的弱监督自顶向下显着性与完全监督的方法的性能，并实现最先进的性能。在7个具有挑战性的数据集上进行实验，并将定量结果与4个不同应用的36个密切相关的方法进行比较。

##### URL
[https://arxiv.org/abs/1611.05345](https://arxiv.org/abs/1611.05345)

##### PDF
[https://arxiv.org/pdf/1611.05345](https://arxiv.org/pdf/1611.05345)

