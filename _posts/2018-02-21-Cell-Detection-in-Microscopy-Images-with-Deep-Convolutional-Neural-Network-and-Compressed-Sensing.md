---
layout: post
title: "Cell Detection in Microscopy Images with Deep Convolutional Neural Network and Compressed Sensing"
date: 2018-02-21 00:11:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Knowledge CNN Optimization Deep_Learning Detection
author: Yao Xue, Nilanjan Ray
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to automatically detect certain types of cells or cellular subunits in microscopy images is of significant interest to a wide range of biomedical research and clinical practices. Cell detection methods have evolved from employing hand-crafted features to deep learning-based techniques. The essential idea of these methods is that their cell classifiers or detectors are trained in the pixel space, where the locations of target cells are labeled. In this paper, we seek a different route and propose a convolutional neural network (CNN)-based cell detection method that uses encoding of the output pixel space. For the cell detection problem, the output space is the sparsely labeled pixel locations indicating cell centers. We employ random projections to encode the output space to a compressed vector of fixed dimension. Then, CNN regresses this compressed vector from the input pixels. Furthermore, it is possible to stably recover sparse cell locations on the output pixel space from the predicted compressed vector using $L_1$-norm optimization. In the past, output space encoding using compressed sensing (CS) has been used in conjunction with linear and non-linear predictors. To the best of our knowledge, this is the first successful use of CNN with CS-based output space encoding. We made substantial experiments on several benchmark datasets, where the proposed CNN + CS framework (referred to as CNNCS) achieved the highest or at least top-3 performance in terms of F1-score, compared with other state-of-the-art methods.

##### Abstract (translated by Google)
在显微图像中自动检测某些类型的细胞或细胞亚基的能力对于广泛的生物医学研究和临床实践具有重要意义。细胞检测方法已从使用手工特征发展到深度学习为基础的技术。这些方法的基本思想是，它们的细胞分类器或检测器在像素空间中进行训练，其中靶细胞的位置被标记。在本文中，我们寻求不同的路线，并提出一种基于卷积神经网络（CNN）的细胞检测方法，该方法使用输出像素空间的编码。对于单元检测问题，输出空间是指示单元中心的稀疏标记的像素位置。我们采用随机投影将输出空间编码为固定维度的压缩矢量。然后，CNN从输入像素中回归该压缩矢量。此外，可以使用$ L_1 $ -norm优化从预测的压缩矢量稳定地恢复输出像素空间上的稀疏单元位置。在过去，使用压缩感测（CS）的输出空间编码已经与线性和非线性预测器一起使用。就我们所知，这是第一次成功使用CNN和基于CS的输出空间编码。我们对几个基准数据集进行了实质性的实验，其中与其他最先进的方法相比，所提出的CNN + CS框架（称为CNNCS）在F1分数方面达到最高或至少前三的性能。

##### URL
[http://arxiv.org/abs/1708.03307](http://arxiv.org/abs/1708.03307)

##### PDF
[http://arxiv.org/pdf/1708.03307](http://arxiv.org/pdf/1708.03307)

