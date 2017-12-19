---
layout: post
title: "FaceNet: A Unified Embedding for Face Recognition and Clustering"
date: 2015-06-17 23:35:47
categories: arXiv_CV
tags: arXiv_CV Face Embedding CNN Deep_Learning Recognition Face_Recognition
author: Florian Schroff, Dmitry Kalenichenko, James Philbin
mathjax: true
---

* content
{:toc}

##### Abstract
Despite significant recent advances in the field of face recognition, implementing face verification and recognition efficiently at scale presents serious challenges to current approaches. In this paper we present a system, called FaceNet, that directly learns a mapping from face images to a compact Euclidean space where distances directly correspond to a measure of face similarity. Once this space has been produced, tasks such as face recognition, verification and clustering can be easily implemented using standard techniques with FaceNet embeddings as feature vectors. Our method uses a deep convolutional network trained to directly optimize the embedding itself, rather than an intermediate bottleneck layer as in previous deep learning approaches. To train, we use triplets of roughly aligned matching / non-matching face patches generated using a novel online triplet mining method. The benefit of our approach is much greater representational efficiency: we achieve state-of-the-art face recognition performance using only 128-bytes per face. On the widely used Labeled Faces in the Wild (LFW) dataset, our system achieves a new record accuracy of 99.63%. On YouTube Faces DB it achieves 95.12%. Our system cuts the error rate in comparison to the best published result by 30% on both datasets. We also introduce the concept of harmonic embeddings, and a harmonic triplet loss, which describe different versions of face embeddings (produced by different networks) that are compatible to each other and allow for direct comparison between each other.

##### Abstract (translated by Google)
尽管人脸识别领域取得了重大进展，但是大规模实施人脸验证和识别对现有的方法提出了严峻的挑战。在本文中，我们提出了一个称为FaceNet的系统，该系统直接学习从人脸图像到紧凑的欧几里得空间的映射，其中距离直接对应于面部相似性度量。一旦产生了这个空间，使用FaceNet嵌入作为特征向量的标准技术可以容易地实现诸如人脸识别，验证和聚类的任务。我们的方法使用深度卷积网络来训练直接优化嵌入本身，而不是像以前的深度学习方法那样是一个中间瓶颈层。为了训练，我们使用三联的大致匹配的匹配/不匹配的面片使用新的在线三重采矿方法生成。我们的方法的好处是更有代表性的效率：我们实现最新的人脸识别性能只使用每个人脸128字节。在广泛使用的野外标记人脸（LFW）数据集中，我们的系统实现了99.63％的新纪录精确度。在YouTube Faces数据库，它达到了95.12％。与两个数据集上的最佳公布结果相比，我们的系统将错误率降低了30％。我们还介绍了谐波嵌入和谐波三重损失的概念，它们描述了不同版本的（由不同网络产生的）不同版本的相互兼容并允许直接相互比较的版本。

##### URL
[https://arxiv.org/abs/1503.03832](https://arxiv.org/abs/1503.03832)

##### PDF
[https://arxiv.org/pdf/1503.03832](https://arxiv.org/pdf/1503.03832)

