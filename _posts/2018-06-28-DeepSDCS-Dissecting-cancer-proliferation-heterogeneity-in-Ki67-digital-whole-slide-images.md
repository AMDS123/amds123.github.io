---
layout: post
title: "DeepSDCS: Dissecting cancer proliferation heterogeneity in Ki67 digital whole slide images"
date: 2018-06-28 09:43:07
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Deep_Learning Detection Gradient_Descent
author: Priya Lakshmi Narayanan, Shan E Ahmed Raza, Andrew Dodson, Barry Gusterson, Mitchell Dowsett, Yinyin Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Ki67 is an important biomarker for breast cancer. Classification of positive and negative Ki67 cells in histology slides is a common approach to determine cancer proliferation status. However, there is a lack of generalizable and accurate methods to automate Ki67 scoring in large-scale patient cohorts. In this work, we have employed a novel deep learning technique based on hypercolumn descriptors for cell classification in Ki67 images. Specifically, we developed the Simultaneous Detection and Cell Segmentation (DeepSDCS) network to perform cell segmentation and detection. VGG16 network was used for the training and fine tuning to training data. We extracted the hypercolumn descriptors of each cell to form the vector of activation from specific layers to capture features at different granularity. Features from these layers that correspond to the same pixel were propagated using a stochastic gradient descent optimizer to yield the detection of the nuclei and the final cell segmentations. Subsequently, seeds generated from cell segmentation were propagated to a spatially constrained convolutional neural network for the classification of the cells into stromal, lymphocyte, Ki67-positive cancer cell, and Ki67-negative cancer cell. We validated its accuracy in the context of a large-scale clinical trial of oestrogen-receptor-positive breast cancer. We achieved 99.06% and 89.59% accuracy on two separate test sets of Ki67 stained breast cancer dataset comprising biopsy and whole-slide images.

##### Abstract (translated by Google)
Ki67是乳腺癌的重要生物标志物。组织学切片中阳性和阴性Ki67细胞的分类是确定癌症增殖状态的常用方法。然而，在大规模患者队列中缺乏可自动化Ki67评分的一般化和精确方法。在这项工作中，我们采用了基于超列描述符的新型深度学习技术，用于Ki67图像中的细胞分类。具体来说，我们开发了同时检测和细胞分割（DeepSDCS）网络来执行细胞分割和检测。 VGG16网络用于培训和微调培训数据。我们提取每个单元格的超列描述符，以形成特定图层的激活矢量，以不同粒度捕捉特征。来自这些层的对应于相同像素的特征使用随机梯度下降优化器来传播以产生核和最终细胞分割的检测。随后，从细胞分割产生的种子被传播到空间受限的卷积神经网络，用于将细胞分类为基质，淋巴细胞，Ki67阳性癌细胞和Ki67阴性癌细胞。我们在雌激素受体阳性乳腺癌的大规模临床试验中验证了它的准确性。我们在包含活检和整张幻灯片图像的两组独立的Ki67染色乳腺癌数据集中获得了99.06％和89.59％的准确性。

##### URL
[http://arxiv.org/abs/1806.10850](http://arxiv.org/abs/1806.10850)

##### PDF
[http://arxiv.org/pdf/1806.10850](http://arxiv.org/pdf/1806.10850)

