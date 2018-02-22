---
layout: post
title: "Self Paced Deep Learning for Weakly Supervised Object Detection"
date: 2018-02-21 16:33:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Deep_Learning Detection
author: Enver Sangineto, Moin Nabi, Dubravko Culibrk, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
In a weakly-supervised scenario object detectors need to be trained using image-level annotation alone. Since bounding-box-level ground truth is not available, most of the solutions proposed so far are based on an iterative, Multiple Instance Learning framework in which the current classifier is used to select the highest-confidence boxes in each image, which are treated as pseudo-ground truth in the next training iteration. However, the errors of an immature classifier can make the process drift, usually introducing many of false positives in the training dataset. To alleviate this problem, we propose in this paper a training protocol based on the self-paced learning paradigm. The main idea is to iteratively select a subset of images and boxes that are the most reliable, and use them for training. While in the past few years similar strategies have been adopted for SVMs and other classifiers, we are the first showing that a self-paced approach can be used with deep-network-based classifiers in an end-to-end training pipeline. The method we propose is built on the fully-supervised Fast-RCNN architecture and can be applied to similar architectures which represent the input image as a bag of boxes. We show state-of-the-art results on Pascal VOC 2007, Pascal VOC 2010 and ILSVRC 2013. On ILSVRC 2013 our results based on a low-capacity AlexNet network outperform even those weakly-supervised approaches which are based on much higher-capacity networks.

##### Abstract (translated by Google)
在弱监督场景中，物体检测器需要单独使用图像级注释进行训练。由于边界框级别的基本事实不可用，迄今为止提出的大多数解决方案都基于迭代的多实例学习框架，其中使用当前分类器来选择每个图像中的最高置信度框，其被处理作为下一次训练迭代中的伪基础事实。然而，未成熟分类器的误差会使得过程漂移，通常会在训练数据集中引入许多误报。为了缓解这个问题，我们在本文中提出了一个基于自我学习范式的培训协议。主要想法是迭代地选择最可靠的图像和盒子的子集，并将其用于训练。尽管在过去几年中，SVM和其他分类器采用了类似的策略，但我们首次表明，可以在端到端培训管道中使用基于深度网络的分类器的自定进度方法。我们提出的方法建立在完全监督的Fast-RCNN架构之上，可以应用于将输入图像表示为一包盒子的类似体系结构。我们在Pascal VOC 2007，Pascal VOC 2010和ILSVRC 2013上展示了最先进的结果。在ILSVRC 2013上，我们基于低容量AlexNet网络的结果甚至胜过那些基于更高容量的弱监督方法网络。

##### URL
[http://arxiv.org/abs/1605.07651](http://arxiv.org/abs/1605.07651)

##### PDF
[http://arxiv.org/pdf/1605.07651](http://arxiv.org/pdf/1605.07651)

