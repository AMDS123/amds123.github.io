---
layout: post
title: "Quality Aware Network for Set to Set Recognition"
date: 2017-04-11 15:47:41
categories: arXiv_CV
tags: arXiv_CV Re-identification QA Face Person_Re-identification Embedding Recognition
author: Yu Liu, Junjie Yan, Wanli Ouyang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper targets on the problem of set to set recognition, which learns the metric between two image sets. Images in each set belong to the same identity. Since images in a set can be complementary, they hopefully lead to higher accuracy in practical applications. However, the quality of each sample cannot be guaranteed, and samples with poor quality will hurt the metric. In this paper, the quality aware network (QAN) is proposed to confront this problem, where the quality of each sample can be automatically learned although such information is not explicitly provided in the training stage. The network has two branches, where the first branch extracts appearance feature embedding for each sample and the other branch predicts quality score for each sample. Features and quality scores of all samples in a set are then aggregated to generate the final feature embedding. We show that the two branches can be trained in an end-to-end manner given only the set-level identity annotation. Analysis on gradient spread of this mechanism indicates that the quality learned by the network is beneficial to set-to-set recognition and simplifies the distribution that the network needs to fit. Experiments on both face verification and person re-identification show advantages of the proposed QAN. The source code and network structure can be downloaded at this https URL

##### Abstract (translated by Google)
本文针对设置识别问题，即学习两个图像集之间的度量。每组中的图像属于相同的身份。由于集合中的图像可以互补，所以希望在实际应用中有更高的精度。但是，每个样品的质量都不能保证，质量差的样品会损害这个指标。为了解决这个问题，本文提出了质量意识网络（QAN），即每个样本的质量可以自动学习，尽管这些信息在训练阶段没有明确提供。网络有两个分支，第一个分支为每个样本提取外观特征嵌入，另一个分支预测每个样本的质量分数。集合中的所有样本的特征和质量分数然后被汇总以产生最终的特征嵌入。我们展示了这两个分支可以在只给定集合标识注释的情况下以端到端的方式进行训练。这种机制的梯度扩展分析表明，网络学习的质量有利于集合识别，并简化了网络所需的分布。对人脸验证和人员重新识别的实验显示了所提出的QAN的优点。源代码和网络结构可以在这个https URL下载

##### URL
[https://arxiv.org/abs/1704.03373](https://arxiv.org/abs/1704.03373)

##### PDF
[https://arxiv.org/pdf/1704.03373](https://arxiv.org/pdf/1704.03373)

