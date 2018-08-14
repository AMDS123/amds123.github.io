---
layout: post
title: "Mapping Auto-context Decision Forests to Deep ConvNets for Semantic Segmentation"
date: 2018-08-13 12:43:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Semantic_Segmentation Relation
author: David L. Richmond, Dagmar Kainmueller, Michael Y. Yang, Eugene W. Myers, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the task of pixel-wise semantic segmentation given a small set of labeled training images. Among two of the most popular techniques to address this task are Decision Forests (DF) and Neural Networks (NN). In this work, we explore the relationship between two special forms of these techniques: stacked DFs (namely Auto-context) and deep Convolutional Neural Networks (ConvNet). Our main contribution is to show that Auto-context can be mapped to a deep ConvNet with novel architecture, and thereby trained end-to-end. This mapping can be used as an initialization of a deep ConvNet, enabling training even in the face of very limited amounts of training data. We also demonstrate an approximate mapping back from the refined ConvNet to a second stacked DF, with improved performance over the original. We experimentally verify that these mappings outperform stacked DFs for two different applications in computer vision and biology: Kinect-based body part labeling from depth images, and somite segmentation in microscopy images of developing zebrafish. Finally, we revisit the core mapping from a Decision Tree (DT) to a NN, and show that it is also possible to map a fuzzy DT, with sigmoidal split decisions, to a NN. This addresses multiple limitations of the previous mapping, and yields new insights into the popular Rectified Linear Unit (ReLU), and more recently proposed concatenated ReLU (CReLU), activation functions.

##### Abstract (translated by Google)
我们考虑给出一小组标记训练图像的逐像素语义分割的任务。解决这一任务的两种最流行的技术是决策森林（DF）和神经网络（NN）。在这项工作中，我们探索了这些技术的两种特殊形式之间的关系：堆叠DF（即自动上下文）和深度卷积神经网络（ConvNet）。我们的主要贡献是展示自动上下文可以映射到具有新颖架构的深度ConvNet，从而进行端到端的训练。该映射可用作深度ConvNet的初始化，即使面对非常有限的训练数据也能够进行训练。我们还展示了从精致的ConvNet到第二个堆叠DF的近似映射，其性能优于原始的。我们通过实验验证这些映射在计算机视觉和生物学中的两种不同应用中优于堆叠DF：基于Kinect的身体部位从深度图像标记，以及在发展中斑马鱼的显微镜图像中的体节分割。最后，我们重新审视从决策树（DT）到NN的核心映射，并且表明还可以将具有S形分裂决策的模糊DT映射到NN。这解决了先前映射的多个局限性，并且产生了对流行的整流线性单元（ReLU）以及最近提出的级联ReLU（CReLU）激活函数的新见解。

##### URL
[http://arxiv.org/abs/1507.07583](http://arxiv.org/abs/1507.07583)

##### PDF
[http://arxiv.org/pdf/1507.07583](http://arxiv.org/pdf/1507.07583)

