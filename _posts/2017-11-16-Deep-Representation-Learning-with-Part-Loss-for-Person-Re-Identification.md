---
layout: post
title: "Deep Representation Learning with Part Loss for Person Re-Identification"
date: 2017-11-16 13:00:23
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Represenation_Learning Classification
author: Hantao Yao, Shiliang Zhang, Yongdong Zhang, Jintao Li, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Learning discriminative representations for unseen person images is critical for person Re-Identification (ReID). Most of current approaches learn deep representations in classification tasks, which essentially minimize the empirical classification risk on the training set. As shown in our experiments, such representations commonly focus on several body parts discriminative to the training set, rather than the entire human body. Inspired by the structural risk minimization principle in SVM, we revise the traditional deep representation learning procedure to minimize both the empirical classification risk and the representation learning risk. The representation learning risk is evaluated by the proposed part loss, which automatically generates several parts for an image, and computes the person classification loss on each part separately. Compared with traditional global classification loss, simultaneously considering multiple part loss enforces the deep network to focus on the entire human body and learn discriminative representations for different parts. Experimental results on three datasets, i.e., Market1501, CUHK03, VIPeR, show that our representation outperforms the existing deep representations.

##### Abstract (translated by Google)
为看不见的人员图像学习歧视性表示对于人员重新识别（ReID）是至关重要的。目前大多数方法在分类任务中学习深度表示，这基本上使训练集上的经验分类风险最小化。如我们的实验所示，这样的表示通常集中在几个身体部位，而不是整个人体。受支持向量机中结构风险最小化原则的启发，我们修正了传统深度表示学习过程，使经验分类风险和表征学习风险最小化。表示学习风险是通过建议零件损失进行评估，自动生成一个图像的几个部分，并分别计算每个部分的人分类损失。与传统的全局分类损失相比，同时考虑多个部分的损失，实施深度网络关注整个人体，学习不同部分的判别表征。在三个数据集，即Market1501，CUHK03，VIPeR上的实验结果表明，我们的表示优于现有的深度表示。

##### URL
[https://arxiv.org/abs/1707.00798](https://arxiv.org/abs/1707.00798)

##### PDF
[https://arxiv.org/pdf/1707.00798](https://arxiv.org/pdf/1707.00798)

