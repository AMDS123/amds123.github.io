---
layout: post
title: "Multiregion Bilinear Convolutional Neural Networks for Person Re-Identification"
date: 2017-09-06 14:38:55
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Embedding CNN Classification
author: Evgeniya Ustinova, Yaroslav Ganin, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose a new architecture for person re-identification. As the task of re-identification is inherently associated with embedding learning and non-rigid appearance description, our architecture is based on the deep bilinear convolutional network (Bilinear-CNN) that has been proposed recently for fine-grained classification of highly non-rigid objects. While the last stages of the original Bilinear-CNN architecture completely removes the geometric information from consideration by performing orderless pooling, we observe that a better embedding can be learned by performing bilinear pooling in a more local way, where each pooling is confined to a predefined region. Our architecture thus represents a compromise between traditional convolutional networks and bilinear CNNs and strikes a balance between rigid matching and completely ignoring spatial information. We perform the experimental validation of the new architecture on the three popular benchmark datasets (Market-1501, CUHK01, CUHK03), comparing it to baselines that include Bilinear-CNN as well as prior art. The new architecture outperforms the baseline on all three datasets, while performing better than state-of-the-art on two out of three. The code and the pretrained models of the approach can be found at this https URL

##### Abstract (translated by Google)
在这项工作中，我们提出了一个新的人员重新识别体系结构。由于重新识别的任务与嵌入学习和非刚性外观描述有着内在的联系，因此我们的体系结构基于最近提出的深度双线性卷积网络（Bilinear-CNN），用于高度非刚性的细粒度分类对象。虽然最初的Bilinear-CNN体系结构的最后阶段通过执行无序池来完全消除几何信息，但我们观察到通过以更局部的方式执行双线性池可以学习到更好的嵌入，其中每个池被限制在预定义地区。因此，我们的体系结构代表了传统卷积网络和双线性CNN之间的折衷，并在刚性匹配和完全忽略空间信息之间取得了平衡。我们在三个受欢迎的基准数据集（Market-1501，CUHK01，CUHK03）上对新架构进行了实验验证，并将其与包括Bilinear-CNN以及现有技术的基线进行比较。新的体系结构在三个数据集上的表现均优于基准，而三分之二的表现则优于现有技术。该方法的代码和预训练模型可以在https网址找到

##### URL
[https://arxiv.org/abs/1512.05300](https://arxiv.org/abs/1512.05300)

##### PDF
[https://arxiv.org/pdf/1512.05300](https://arxiv.org/pdf/1512.05300)

