---
layout: post
title: "Visual Understanding via Multi-Feature Shared Learning with Global Consistency"
date: 2015-09-09 10:07:11
categories: arXiv_CV
tags: arXiv_CV Regularization Attention CNN Optimization Classification Prediction Recognition
author: Lei Zhang, David Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Image/video data is usually represented with multiple visual features. Fusion of multi-source information for establishing the attributes has been widely recognized. Multi-feature visual recognition has recently received much attention in multimedia applications. This paper studies visual understanding via a newly proposed l_2-norm based multi-feature shared learning framework, which can simultaneously learn a global label matrix and multiple sub-classifiers with the labeled multi-feature data. Additionally, a group graph manifold regularizer composed of the Laplacian and Hessian graph is proposed for better preserving the manifold structure of each feature, such that the label prediction power is much improved through the semi-supervised learning with global label consistency. For convenience, we call the proposed approach Global-Label-Consistent Classifier (GLCC). The merits of the proposed method include: 1) the manifold structure information of each feature is exploited in learning, resulting in a more faithful classification owing to the global label consistency; 2) a group graph manifold regularizer based on the Laplacian and Hessian regularization is constructed; 3) an efficient alternative optimization method is introduced as a fast solver owing to the convex sub-problems. Experiments on several benchmark visual datasets for multimedia understanding, such as the 17-category Oxford Flower dataset, the challenging 101-category Caltech dataset, the YouTube & Consumer Videos dataset and the large-scale NUS-WIDE dataset, demonstrate that the proposed approach compares favorably with the state-of-the-art algorithms. An extensive experiment on the deep convolutional activation features also show the effectiveness of the proposed approach. The code is available on this http URL

##### Abstract (translated by Google)
图像/视频数据通常用多个视觉特征表示。融合多源信息来建立属性已被广泛认可。多特征视觉识别最近在多媒体应用中受到了很多关注。本文通过一个新提出的基于l_2范数的多特征共享学习框架来研究视觉理解，该框架可以同时学习标注多特征数据的全局标签矩阵和多个子分类器。另外，为了更好地保持每个特征的流形结构，提出了一种由拉普拉斯算子和Hessian图组成的图形流形正则化规则，通过半监督学习和全局标签一致性，大大提高了标签预测能力。为方便起见，我们称之为全局标签一致分类器（GLCC）。该方法的优点包括：1）在学习中利用各特征的流形结构信息，由于全局标签的一致性，导致更为忠实的分类; 2）构造了基于Laplacian和Hessian正则化的群图流形正则化方法; 3）由于存在凸子问题，引入了一种高效的替代优化方法作为快速求解器。对于多媒体理解的几个基准视觉数据集（例如17类牛津花数据集，具有挑战性的101类加州数据集，YouTube和消费者视频数据集以及大规模NUS-WIDE数据集）的实验证明了所提出的方法有利于最先进的算法。对深度卷积激活特征的广泛实验也显示了所提出的方法的有效性。该代码在这个http URL上可用

##### URL
[https://arxiv.org/abs/1505.05233](https://arxiv.org/abs/1505.05233)

##### PDF
[https://arxiv.org/pdf/1505.05233](https://arxiv.org/pdf/1505.05233)

