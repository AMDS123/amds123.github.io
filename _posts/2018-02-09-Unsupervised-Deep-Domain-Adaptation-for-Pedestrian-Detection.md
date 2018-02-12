---
layout: post
title: "Unsupervised Deep Domain Adaptation for Pedestrian Detection"
date: 2018-02-09 14:15:35
categories: arXiv_CV
tags: arXiv_CV Detection
author: Lihang Liu, Weiyao Lin, Lisheng Wu, Yong Yu, Michael Ying Yang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of unsupervised domain adaptation on the task of pedestrian detection in crowded scenes. First, we utilize an iterative algorithm to iteratively select and auto-annotate positive pedestrian samples with high confidence as the training samples for the target domain. Meanwhile, we also reuse negative samples from the source domain to compensate for the imbalance between the amount of positive samples and negative samples. Second, based on the deep network we also design an unsupervised regularizer to mitigate influence from data noise. More specifically, we transform the last fully connected layer into two sub-layers - an element-wise multiply layer and a sum layer, and add the unsupervised regularizer to further improve the domain adaptation accuracy. In experiments for pedestrian detection, the proposed method boosts the recall value by nearly 30% while the precision stays almost the same. Furthermore, we perform our method on standard domain adaptation benchmarks on both supervised and unsupervised settings and also achieve state-of-the-art results.

##### Abstract (translated by Google)
本文针对拥挤场景下行人检测任务的无监督域自适应问题，首先，我们利用迭代算法迭代选择和自动注释具有高置信度的正面行人样本作为目标域的训练样本。同时，我们也重新使用来源域的负样本来弥补正样本和负样本数量之间的不平衡。其次，基于深度网络，我们还设计了一个无监督正则化器来减轻数据噪声的影响。更具体地说，我们将最后一个完全连接的层转换为两个子层 - 一个元素级乘法层和一个和层，并添加无监督正则化器以进一步提高域适应精度。在行人检测的实验中，所提出的方法将召回值提高近30％，而精度保持几乎相同。此外，我们在有监督和无监督设置下执行标准域适应基准的方法，并获得最新的结果。

##### URL
[http://arxiv.org/abs/1802.03269](http://arxiv.org/abs/1802.03269)

##### PDF
[http://arxiv.org/pdf/1802.03269](http://arxiv.org/pdf/1802.03269)

