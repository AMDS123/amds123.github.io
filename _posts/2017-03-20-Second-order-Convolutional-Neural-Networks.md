---
layout: post
title: "Second-order Convolutional Neural Networks"
date: 2017-03-20 16:05:21
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Kaicheng Yu, Mathieu Salzmann
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) have been successfully applied to many computer vision tasks, such as image classification. By performing linear combinations and element-wise nonlinear operations, these networks can be thought of as extracting solely first-order information from an input image. In the past, however, second-order statistics computed from handcrafted features, e.g., covariances, have proven highly effective in diverse recognition tasks. In this paper, we introduce a novel class of CNNs that exploit second-order statistics. To this end, we design a series of new layers that (i) extract a covariance matrix from convolutional activations, (ii) compute a parametric, second-order transformation of a matrix, and (iii) perform a parametric vectorization of a matrix. These operations can be assembled to form a Covariance Descriptor Unit (CDU), which replaces the fully-connected layers of standard CNNs. Our experiments demonstrate the benefits of our new architecture, which outperform the first-order CNNs, while relying on up to 90% fewer parameters.

##### Abstract (translated by Google)
卷积神经网络（CNNs）已经成功应用于许多计算机视觉任务，如图像分类。通过执行线性组合和按照元素的非线性操作，这些网络可以被认为是从输入图像中仅提取一阶信息。然而在过去，由手工特征（例如协方差）计算的二阶统计已经证明在多种识别任务中非常有效。在本文中，我们引入一个新颖的CNN类，利用二阶统计量。为此，我们设计了一系列新的层次：（i）从卷积激活中提取协方差矩阵;（ii）计算矩阵的参数化二阶变换;以及（iii）执行矩阵的参数化矢量化。这些操作可以被组合成一个协方差描述符单元（CDU），它代替了标准CNN的全连接层。我们的实验证明了我们新架构的优势，该架构优于一阶CNN，同时依赖于多达90％的参数。

##### URL
[https://arxiv.org/abs/1703.06817](https://arxiv.org/abs/1703.06817)

##### PDF
[https://arxiv.org/pdf/1703.06817](https://arxiv.org/pdf/1703.06817)

