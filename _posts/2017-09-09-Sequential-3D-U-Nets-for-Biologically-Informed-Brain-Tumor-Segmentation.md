---
layout: post
title: "Sequential 3D U-Nets for Biologically-Informed Brain Tumor Segmentation"
date: 2017-09-09 15:57:51
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Andrew Beers, Ken Chang, James Brown, Emmett Sartor, CP Mammen, Elizabeth Gerstner, Bruce Rosen, Jayashree Kalpathy-Cramer
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has quickly become the weapon of choice for brain lesion segmentation. However, few existing algorithms pre-configure any biological context of their chosen segmentation tissues, and instead rely on the neural network's optimizer to develop such associations de novo. We present a novel method for applying deep neural networks to the problem of glioma tissue segmentation that takes into account the structured nature of gliomas - edematous tissue surrounding mutually-exclusive regions of enhancing and non-enhancing tumor. We trained multiple deep neural networks with a 3D U-Net architecture in a tree structure to create segmentations for edema, non-enhancing tumor, and enhancing tumor regions. Specifically, training was configured such that the whole tumor region including edema was predicted first, and its output segmentation was fed as input into separate models to predict enhancing and non-enhancing tumor. Our method was trained and evaluated on the publicly available BraTS dataset, achieving Dice scores of 0.882, 0.732, and 0.730 for whole tumor, enhancing tumor and tumor core respectively.

##### Abstract (translated by Google)
深度学习已经迅速成为脑病灶分割的首选武器。然而，很少有现有的算法预先配置他们选择的分割组织的任何生物学背景，而是依赖于神经网络的优化器从头开发这样的关联。我们提出了一种新的方法应用深度神经网络的问题胶质瘤组织分割，考虑到胶质瘤的结构性质 - 水肿组织围绕增强和非增强肿瘤的互斥区域。我们用三维U-Net架构在树状结构中训练多个深度神经网络，以创建水肿，非增强肿瘤和增强肿瘤区域的分割。具体而言，训练被配置为使得包括水肿的整个肿瘤区域被首先预测，并且其输出分割作为输入被馈送到分开的模型中以预测增强和非增强肿瘤。我们的方法在公开的BraTS数据集上进行了训练和评估，实现了对整个肿瘤的DSS评分分别为0.882,0.732和0.730，分别提高了肿瘤和肿瘤的核心。

##### URL
[https://arxiv.org/abs/1709.02967](https://arxiv.org/abs/1709.02967)

##### PDF
[https://arxiv.org/pdf/1709.02967](https://arxiv.org/pdf/1709.02967)

