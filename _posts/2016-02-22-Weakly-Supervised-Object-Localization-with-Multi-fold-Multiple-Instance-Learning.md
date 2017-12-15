---
layout: post
title: "Weakly Supervised Object Localization with Multi-fold Multiple Instance Learning"
date: 2016-02-22 20:26:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised CNN Detection
author: Ramazan Gokberk Cinbis, Jakob Verbeek, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
Object category localization is a challenging problem in computer vision. Standard supervised training requires bounding box annotations of object instances. This time-consuming annotation process is sidestepped in weakly supervised learning. In this case, the supervised information is restricted to binary labels that indicate the absence/presence of object instances in the image, without their locations. We follow a multiple-instance learning approach that iteratively trains the detector and infers the object locations in the positive training images. Our main contribution is a multi-fold multiple instance learning procedure, which prevents training from prematurely locking onto erroneous object locations. This procedure is particularly important when using high-dimensional representations, such as Fisher vectors and convolutional neural network features. We also propose a window refinement method, which improves the localization accuracy by incorporating an objectness prior. We present a detailed experimental evaluation using the PASCAL VOC 2007 dataset, which verifies the effectiveness of our approach.

##### Abstract (translated by Google)
对象类别本地化是计算机视觉中的一个挑战性问题标准的有监督的训练需要对象实例的边界框注解。这个耗时的注释过程在弱监督学习中被回避。在这种情况下，监督信息被限制为指示图像中不存在/存在对象实例的二进制标签，而没有它们的位置。我们遵循多重实例学习方法，迭代地训练探测器并推断正面训练图像中的对象位置。我们的主要贡献是多重多重实例学习过程，防止训练过早锁定到错误的对象位置。当使用高维表示时，如Fisher矢量和卷积神经网络特征，这个过程特别重要。我们还提出了一种窗口细化方法，通过结合先验对象来提高定位精度。我们使用PASCAL VOC 2007数据集提供了详细的实验评估，验证了我们方法的有效性。

##### URL
[https://arxiv.org/abs/1503.00949](https://arxiv.org/abs/1503.00949)

##### PDF
[https://arxiv.org/pdf/1503.00949](https://arxiv.org/pdf/1503.00949)

