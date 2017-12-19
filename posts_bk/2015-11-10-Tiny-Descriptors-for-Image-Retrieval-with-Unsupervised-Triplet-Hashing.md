---
layout: post
title: "Tiny Descriptors for Image Retrieval with Unsupervised Triplet Hashing"
date: 2015-11-10 10:38:37
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding CNN Image_Classification Classification Deep_Learning
author: Jie Lin, Olivier Morère, Julie Petta, Vijay Chandrasekhar, Antoine Veillard
mathjax: true
---

* content
{:toc}

##### Abstract
A typical image retrieval pipeline starts with the comparison of global descriptors from a large database to find a short list of candidate matches. A good image descriptor is key to the retrieval pipeline and should reconcile two contradictory requirements: providing recall rates as high as possible and being as compact as possible for fast matching. Following the recent successes of Deep Convolutional Neural Networks (DCNN) for large scale image classification, descriptors extracted from DCNNs are increasingly used in place of the traditional hand crafted descriptors such as Fisher Vectors (FV) with better retrieval performances. Nevertheless, the dimensionality of a typical DCNN descriptor --extracted either from the visual feature pyramid or the fully-connected layers-- remains quite high at several thousands of scalar values. In this paper, we propose Unsupervised Triplet Hashing (UTH), a fully unsupervised method to compute extremely compact binary hashes --in the 32-256 bits range-- from high-dimensional global descriptors. UTH consists of two successive deep learning steps. First, Stacked Restricted Boltzmann Machines (SRBM), a type of unsupervised deep neural nets, are used to learn binary embedding functions able to bring the descriptor size down to the desired bitrate. SRBMs are typically able to ensure a very high compression rate at the expense of loosing some desirable metric properties of the original DCNN descriptor space. Then, triplet networks, a rank learning scheme based on weight sharing nets is used to fine-tune the binary embedding functions to retain as much as possible of the useful metric properties of the original space. A thorough empirical evaluation conducted on multiple publicly available dataset using DCNN descriptors shows that our method is able to significantly outperform state-of-the-art unsupervised schemes in the target bit range.

##### Abstract (translated by Google)
典型的图像检索流程开始于比较来自大型数据库的全局描述符以找到候选匹配的短列表。一个好的图像描述符是检索流水线的关键，并且应该协调两个相互矛盾的要求：提供尽可能高的召回率和尽可能紧凑的快速匹配。随着深度卷积神经网络（DCNN）最近在大规模图像分类方面取得的成功，从DCNN中提取的描述符越来越多地被用来取代传统的手工描述符，如具有更好检索性能的Fisher矢量（FV）。然而，从视觉特征金字塔或完全连接层中提取的典型DCNN描述符的维度在几千个标量值处仍然相当高。在本文中，我们提出无监督的Triplet Hashing（UTH），一种完全无监督的方法，用于从高维全局描述符中计算非常紧凑的二进制散列（在32-256位范围内）。 UTH由两个连续的深度学习步骤组成。首先，使用堆栈受限玻尔兹曼机（SRBM）（一种无监督深度神经网络）来学习能够使描述符大小降低到期望比特率的二进制嵌入函数。 SRBM通常能够以损失原始DCNN描述符空间的一些期望的度量属性为代价来确保非常高的压缩率。然后，采用基于权重共享网络的排名学习方案对三元网络进行微调，以尽可能多地保留原始空间的有用度量属性。对使用DCNN描述符的多个公开可用数据集进行的彻底的经验评估表明，我们的方法能够在目标比特范围内显着优于最先进的无监督方案。

##### URL
[https://arxiv.org/abs/1511.03055](https://arxiv.org/abs/1511.03055)

##### PDF
[https://arxiv.org/pdf/1511.03055](https://arxiv.org/pdf/1511.03055)

