---
layout: post
title: "A Proximity-Aware Hierarchical Clustering of Faces"
date: 2017-03-14 23:41:45
categories: arXiv_CV
tags: arXiv_CV Face
author: Wei-An Lin, Jun-Cheng Chen, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an unsupervised face clustering algorithm called "Proximity-Aware Hierarchical Clustering" (PAHC) that exploits the local structure of deep representations. In the proposed method, a similarity measure between deep features is computed by evaluating linear SVM margins. SVMs are trained using nearest neighbors of sample data, and thus do not require any external training data. Clusters are then formed by thresholding the similarity scores. We evaluate the clustering performance using three challenging unconstrained face datasets, including Celebrity in Frontal-Profile (CFP), IARPA JANUS Benchmark A (IJB-A), and JANUS Challenge Set 3 (JANUS CS3) datasets. Experimental results demonstrate that the proposed approach can achieve significant improvements over state-of-the-art methods. Moreover, we also show that the proposed clustering algorithm can be applied to curate a set of large-scale and noisy training dataset while maintaining sufficient amount of images and their variations due to nuisance factors. The face verification performance on JANUS CS3 improves significantly by finetuning a DCNN model with the curated MS-Celeb-1M dataset which contains over three million face images.

##### Abstract (translated by Google)
在本文中，我们提出了一种无监督人脸聚类算法，称为“接近感知分级聚类”（PAHC），利用深度表示的局部结构。在所提出的方法中，通过评估线性SVM边界来计算深度特征之间的相似性度量。 SVM使用样本数据的最近邻居进行训练，因此不需要任何外部训练数据。然后通过对相似度分数进行阈值化来形成集群。我们使用三个具有挑战性的无约束人脸数据集（包括Frontal-Profile（CFP）中的名人，IARPA JANUS基准A（IJB-A）和JANUS Challenge Set 3（JANUS CS3）数据集）评估聚类性能。实验结果表明，所提出的方法可以比现有技术方法实现显着的改进。此外，我们还表明，所提出的聚类算法可以用于策划一组大规模和有噪声的训练数据集，同时保持足够数量的图像及其由于干扰因素的变化。 JANUS CS3上的脸部验证性能通过使用包含超过三百万张脸部图像的策划的MS-Celeb-1M数据集对DCNN模型进行微调来显着改善。

##### URL
[https://arxiv.org/abs/1703.04835](https://arxiv.org/abs/1703.04835)

##### PDF
[https://arxiv.org/pdf/1703.04835](https://arxiv.org/pdf/1703.04835)

