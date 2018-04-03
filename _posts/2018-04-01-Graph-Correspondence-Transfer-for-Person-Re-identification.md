---
layout: post
title: "Graph Correspondence Transfer for Person Re-identification"
date: 2018-04-01 01:39:17
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification
author: Qin Zhou, Heng Fan, Shibao Zheng, Hang Su, Xinzhe Li, Shuang Wu, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a graph correspondence transfer (GCT) approach for person re-identification. Unlike existing methods, the GCT model formulates person re-identification as an off-line graph matching and on-line correspondence transferring problem. In specific, during training, the GCT model aims to learn off-line a set of correspondence templates from positive training pairs with various pose-pair configurations via patch-wise graph matching. During testing, for each pair of test samples, we select a few training pairs with the most similar pose-pair configurations as references, and transfer the correspondences of these references to test pair for feature distance calculation. The matching score is derived by aggregating distances from different references. For each probe image, the gallery image with the highest matching score is the re-identifying result. Compared to existing algorithms, our GCT can handle spatial misalignment caused by large variations in view angles and human poses owing to the benefits of patch-wise graph matching. Extensive experiments on five benchmarks including VIPeR, Road, PRID450S, 3DPES and CUHK01 evidence the superior performance of GCT model over other state-of-the-art methods.

##### Abstract (translated by Google)
在本文中，我们提出了一种用于人员重新识别的图形对应转移（GCT）方法。与现有方法不同，GCT模型将人员重新识别作为离线图匹配和在线通信转移问题。具体而言，在训练期间，GCT模型旨在通过面向拼图的图匹配从具有各种姿势对配置的正训练对离线学习一组对应模板。在测试过程中，对于每对测试样本，我们选择几个具有最相似姿势对配置的训练对作为参考，并将这些参考的对应关系传送给测试对以进行特征距离计算。匹配分数通过汇总来自不同参考的距离而得出。对于每个探测图像，具有最高匹配分数的图库图像是重新识别结果。与现有的算法相比，我们的GCT可以处理由视角和人体姿态的巨大变化引起的空间偏差，这是由于面片图形匹配的好处。包括VIPeR，Road，PRID450S，3DPES和CUHK01在内的五个基准的大量实验证明了GCT模型优于其他最先进方法的优越性能。

##### URL
[http://arxiv.org/abs/1804.00242](http://arxiv.org/abs/1804.00242)

##### PDF
[http://arxiv.org/pdf/1804.00242](http://arxiv.org/pdf/1804.00242)

