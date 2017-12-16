---
layout: post
title: "Cell Detection with Deep Convolutional Neural Network and Compressed Sensing"
date: 2017-09-22 04:43:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Knowledge CNN Optimization Deep_Learning Detection
author: Yao Xue, Nilanjan Ray
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to automatically detect certain types of cells or cellular subunits in microscopy images is of significant interest to a wide range of biomedical research and clinical practices. Cell detection methods have evolved from employing hand-crafted features to deep learning-based techniques to locate target cells. The essential idea of these methods is that their cell classifiers or detectors are trained in the pixel space, where the locations of target cells are labeled. In this paper, we seek a different route and propose a convolutional neural network (CNN)-based cell detection method that uses encoding of the output pixel space. For the cell detection problem, the output space is the sparsely labeled pixel locations indicating cell centers. Consequently, we employ random projections to encode the output space to a compressed vector of fixed dimension. Then, CNN regresses this compressed vector from the input pixels. Using $L_1$-norm optimization, we recover sparse cell locations on the output pixel space from the predicted compressed vector. In the past, output space encoding using compressed sensing (CS) has been used in conjunction with linear and non-linear predictors. To the best of our knowledge, this is the first successful use of CNN with CS-based output space encoding. We experimentally demonstrate that proposed CNN + CS framework (referred to as CNNCS) exceeds the accuracy of the state-of-the-art methods on many benchmark datasets for microscopy cell detection. Additionally, we show that CNNCS can exploit ensemble average by using more than one random encodings of the output space. In the AMIDA13 MICCAI grand competition, we achieve the 3rd highest F1-score in all the 17 participated teams. More ranking details are available at this http URL Implementation of CNNCS is available at this https URL

##### Abstract (translated by Google)
在显微镜图像中自动检测某些类型的细胞或细胞亚基的能力对于广泛的生物医学研究和临床实践具有重要意义。细胞检测方法已经从使用手工特征发展到基于深度学习的技术来定位靶细胞。这些方法的基本思想是，他们的细胞分类器或检测器在像素空间中进行训练，在那里标记靶细胞的位置。在本文中，我们寻求不同的路线，并提出一种基于卷积神经网络（CNN）的细胞检测方法，使用输出像素空间的编码。对于细胞检测问题，输出空间是指示细胞中心的稀疏标记的像素位置。因此，我们使用随机投影将输出空间编码为固定维度的压缩矢量。然后，CNN从输入像素中回归这个压缩矢量。使用$ L_1 $ -norm优化，我们从预测的压缩矢量恢复输出像素空间上的稀疏单元位置。过去，使用压缩感测（CS）的输出空间编码已经与线性和非线性预测器一起使用。就我们所知，这是CNN基于CS输出空间编码的首次成功使用。我们通过实验证明，提出的CNN + CS框架（简称CNNCS）超过了许多用于显微镜细胞检测的基准数据集的最先进的方法的准确性。另外，我们表明CNNCS可以利用输出空间的多个随机编码来利用集合平均。在AMIDA13 MICCAI盛大的比赛中，我们在所有17个参赛球队中取得了第三高的F1分数。这个http URL提供了更多的排名详细信息CNNCS的实施可以通过这个https URL获得

##### URL
[https://arxiv.org/abs/1708.03307](https://arxiv.org/abs/1708.03307)

##### PDF
[https://arxiv.org/pdf/1708.03307](https://arxiv.org/pdf/1708.03307)

