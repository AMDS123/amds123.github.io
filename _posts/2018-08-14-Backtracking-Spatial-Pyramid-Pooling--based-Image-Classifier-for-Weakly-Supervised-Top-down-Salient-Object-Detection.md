---
layout: post
title: "Backtracking Spatial Pyramid Pooling -based Image Classifier for Weakly Supervised Top-down Salient Object Detection"
date: 2018-08-14 17:39:11
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Weakly_Supervised Tracking Quantitative Detection
author: Hisham Cholakkal, Jubin Johnson, Deepu Rajan
mathjax: true
---

* content
{:toc}

##### Abstract
Top-down saliency models produce a probability map that peaks at target locations specified by a task/goal such as object detection. They are usually trained in a fully supervised setting involving pixel-level annotations of objects. We propose a weakly supervised top-down saliency framework using only binary labels that indicate the presence/absence of an object in an image. First, the probabilistic contribution of each image region to the confidence of a CNN-based image classifier is computed through a backtracking strategy to produce top-down saliency. From a set of saliency maps of an image produced by fast bottom-up saliency approaches, we select the best saliency map suitable for the top-down task. The selected bottom-up saliency map is combined with the top-down saliency map. Features having high combined saliency are used to train a linear SVM classifier to estimate feature saliency. This is integrated with combined saliency and further refined through a multi-scale superpixel-averaging of saliency map. We evaluate the performance of the proposed weakly supervised topdown saliency and achieve comparable performance with fully supervised approaches. Experiments are carried out on seven challenging datasets and quantitative results are compared with 40 closely related approaches across 4 different applications.

##### Abstract (translated by Google)
自上而下显着性模型产生概率图，该概率图在由任务/目标（例如对象检测）指定的目标位置处达到峰值。它们通常在完全监督的环境中进行训练，包括对象的像素级注释。我们提出了一种弱监督的自上而下的显着性框架，它仅使用二进制标签来指示图像中是否存在对象。首先，通过回溯策略计算每个图像区域对基于CNN的图像分类器的置信度的概率贡献，以产生自上而下的显着性。从快速自下而上显着性方法生成的图像的一组显着性图中，我们选择适合自上而下任务的最佳显着性图。选定的自下而上显着性图与自上而下的显着性图组合。具有高组合显着性的特征用于训练线性SVM分类器以估计特征显着性。这与综合显着性相结合，并通过显着性图的多尺度超像素平均值进一步细化。我们评估所提议的弱监督自上而下显着性的表现，并通过完全监督的方法实现可比性能。对七个具有挑战性的数据集进行了实验，并将定量结果与4种不同应用中的40种密切相关的方法进行了比较。

##### URL
[http://arxiv.org/abs/1611.05345](http://arxiv.org/abs/1611.05345)

##### PDF
[http://arxiv.org/pdf/1611.05345](http://arxiv.org/pdf/1611.05345)

