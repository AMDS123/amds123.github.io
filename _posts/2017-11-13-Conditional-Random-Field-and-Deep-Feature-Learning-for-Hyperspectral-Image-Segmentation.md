---
layout: post
title: "Conditional Random Field and Deep Feature Learning for Hyperspectral Image Segmentation"
date: 2017-11-13 09:18:25
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Inference Classification Relation
author: Fahim Irfan Alam, Jun Zhou, Alan Wee-Chung Liew, Xiuping Jia, Jocelyn Chanussot, Yongsheng Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Image segmentation is considered to be one of the critical tasks in hyperspectral remote sensing image processing. Recently, convolutional neural network (CNN) has established itself as a powerful model in segmentation and classification by demonstrating excellent performances. The use of a graphical model such as a conditional random field (CRF) contributes further in capturing contextual information and thus improving the segmentation performance. In this paper, we propose a method to segment hyperspectral images by considering both spectral and spatial information via a combined framework consisting of CNN and CRF. We use multiple spectral cubes to learn deep features using CNN, and then formulate deep CRF with CNN-based unary and pairwise potential functions to effectively extract the semantic correlations between patches consisting of three-dimensional data cubes. Effective piecewise training is applied in order to avoid the computationally expensive iterative CRF inference. Furthermore, we introduce a deep deconvolution network that improves the segmentation masks. We also introduce a new dataset and experimented our proposed method on it along with several widely adopted benchmark datasets to evaluate the effectiveness of our method. By comparing our results with those from several state-of-the-art models, we show the promising potential of our method.

##### Abstract (translated by Google)
图像分割被认为是高光谱遥感图像处理的关键任务之一。最近，卷积神经网络（CNN）已经证明自己是一个强大的分割和分类模型，表现出优异的性能。使用诸如条件随机场（CRF）之类的图形模型进一步有助于捕获上下文信息，从而改善分段性能。在本文中，我们提出了一种方法来分割高光谱图像，通过考虑光谱和空间信息通过CNN和CRF组成的组合框架。利用多光谱立方体，利用CNN学习深度特征，利用CNN一元和二元势函数构造深CRF，有效提取三维数据立方体拼块之间的语义相关性。有效的分段训练被应用，以避免计算昂贵的迭代CRF推断。此外，我们引入了一个深度反卷积网络，改善了分割掩模。我们还引入了一个新的数据集，并试验了我们提出的方法以及几个广泛采用的基准数据集来评估我们的方法的有效性。通过比较我们的结果与几个最先进的模型的结果，我们展示了我们的方法的潜力。

##### URL
[https://arxiv.org/abs/1711.04483](https://arxiv.org/abs/1711.04483)

##### PDF
[https://arxiv.org/pdf/1711.04483](https://arxiv.org/pdf/1711.04483)

