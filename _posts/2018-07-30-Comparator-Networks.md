---
layout: post
title: "Comparator Networks"
date: 2018-07-30 16:54:21
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Face Image_Classification Classification Recognition Face_Recognition
author: Weidi Xie, Li Shen, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
The objective of this work is set-based verification, e.g. to decide if two sets of images of a face are of the same person or not. The traditional approach to this problem is to learn to generate a feature vector per image, aggregate them into one vector to represent the set, and then compute the cosine similarity between sets. Instead, we design a neural network architecture that can directly learn set-wise verification. Our contributions are: (i) We propose a Deep Comparator Network (DCN) that can ingest a pair of sets (each may contain a variable number of images) as inputs, and compute a similarity between the pair--this involves attending to multiple discriminative local regions (landmarks), and comparing local descriptors between pairs of faces; (ii) To encourage high-quality representations for each set, internal competition is introduced for recalibration based on the landmark score; (iii) Inspired by image retrieval, a novel hard sample mining regime is proposed to control the sampling process, such that the DCN is complementary to the standard image classification models. Evaluations on the IARPA Janus face recognition benchmarks show that the comparator networks outperform the previous state-of-the-art results by a large margin.

##### Abstract (translated by Google)
这项工作的目标是基于集合的验证，例如判断一组面部的两组图像是否属于同一个人。解决这个问题的传统方法是学习为每个图像生成一个特征向量，将它们聚合成一个向量来表示该集合，然后计算集合之间的余弦相似度。相反，我们设计了一个可以直接学习逐集验证的神经网络架构。我们的贡献是：（i）我们提出了一个深度比较器网络（DCN），它可以摄取一对集合（每个集合可能包含可变数量的图像）作为输入，并计算这对集合之间的相似性 - 这涉及参与多个判别性局部区域（地标），并比较面对之间的局部描述符; （ii）为了鼓励每组的高质量陈述，引入内部竞争以根据具有里程碑意义的分数进行重新校准; （iii）受图像检索的启发，提出了一种新的硬样本挖掘机制来控制采样过程，使得DCN与标准图像分类模型互补。对IARPA Janus人脸识别基准的评估表明，比较器网络在很大程度上优于先前的最先进结果。

##### URL
[http://arxiv.org/abs/1807.11440](http://arxiv.org/abs/1807.11440)

##### PDF
[http://arxiv.org/pdf/1807.11440](http://arxiv.org/pdf/1807.11440)

