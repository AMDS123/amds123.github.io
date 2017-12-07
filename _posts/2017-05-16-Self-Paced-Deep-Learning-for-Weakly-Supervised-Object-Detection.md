---
layout: post
title: "Self Paced Deep Learning for Weakly Supervised Object Detection"
date: 2017-05-16 16:04:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Deep_Learning Detection
author: Enver Sangineto, Moin Nabi, Dubravko Culibrk, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
In a weakly-supervised scenario object detectors need to be trained using image-level annotation alone. Since bounding-box-level ground truth is not available, most of the solutions proposed so far are based on an iterative, Multiple Instance Learning framework in which the current classifier is used to select the highest-confidence boxes in each image, which are treated as pseudo-ground truth in the next training iteration. However, the errors of an immature classifier can make the process drift, usually introducing a lot of false positives in the training dataset. In this paper we propose a self-paced learning protocol to alleviate this problem. The main idea is to iteratively select a subset of images and boxes that are the most reliable, and use them for training. While in the past few years similar strategies have been adopted for SVMs and other classifiers, we are the first showing that a self-paced approach can be used with deep-network-based classifiers in an end-to-end training pipeline. The method we propose is built on the fully-supervised Fast-RCNN architecture and can be applied to similar architectures which represent the input image as a bag of boxes. Using a relatively simple architecture based on Fast-RCNN and AlexNet, we show state-of-the-art results on Pascal VOC 2007 and ILSVRC 2013. On ILSVRC 2013 our low-capacity network outperforms even those weakly-supervised approaches which are based on much higher-capacity networks.

##### Abstract (translated by Google)
在弱监督场景中，物体检测器需要单独使用图像级注释进行训练。由于边界框级别的基本事实不可用，迄今为止提出的大多数解决方案都是基于迭代的，多实例学习框架，其中当前分类器被用来选择每个图像中的最高置信度框，其被处理作为下一次训练迭代中的伪基础事实。然而，不成熟的分类器的错误会使得过程漂移，通常在训练数据集中引入大量误报。在本文中，我们提出了一个自学的学习协议来缓解这个问题。主要思想是迭代地选择最可靠的图像和盒子的一个子集，并将其用于训练。在过去的几年中，类似的策略已经被用于支持向量机和其他分类器，我们首先展示了一个自定进度的方法可以在端到端的训练管道中与基于深度网络的分类器一起使用。我们提出的方法建立在完全监督的Fast-RCNN架构之上，可以应用于类似的体系结构，将输入图像表示为一包盒子。使用基于Fast-RCNN和AlexNet的相对简单的架构，我们在Pascal VOC 2007和ILSVRC 2013上展示了最新的结果。在ILSVRC 2013上，我们的低容量网络甚至胜过那些基于容量更高的网络。

##### URL
[https://arxiv.org/abs/1605.07651](https://arxiv.org/abs/1605.07651)

##### PDF
[https://arxiv.org/pdf/1605.07651](https://arxiv.org/pdf/1605.07651)

