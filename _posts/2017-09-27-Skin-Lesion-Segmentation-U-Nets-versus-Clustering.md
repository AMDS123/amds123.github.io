---
layout: post
title: "Skin Lesion Segmentation: U-Nets versus Clustering"
date: 2017-09-27 22:46:29
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Bill S. Lin, Kevin Michael, Shivam Kalra, H.R. Tizhoosh
mathjax: true
---

* content
{:toc}

##### Abstract
Many automatic skin lesion diagnosis systems use segmentation as a preprocessing step to diagnose skin conditions because skin lesion shape, border irregularity, and size can influence the likelihood of malignancy. This paper presents, examines and compares two different approaches to skin lesion segmentation. The first approach uses U-Nets and introduces a histogram equalization based preprocessing step. The second approach is a C-Means clustering based approach that is much simpler to implement and faster to execute. The Jaccard Index between the algorithm output and hand segmented images by dermatologists is used to evaluate the proposed algorithms. While many recently proposed deep neural networks to segment skin lesions require a significant amount of computational power for training (i.e., computer with GPUs), the main objective of this paper is to present methods that can be used with only a CPU. This severely limits, for example, the number of training instances that can be presented to the U-Net. Comparing the two proposed algorithms, U-Nets achieved a significantly higher Jaccard Index compared to the clustering approach. Moreover, using the histogram equalization for preprocessing step significantly improved the U-Net segmentation results.

##### Abstract (translated by Google)
许多自动皮肤病变诊断系统使用分割作为预处理步骤来诊断皮肤状况，因为皮肤病变形状，边界不规则性和大小可以影响恶性的可能性。本文介绍，检查和比较两种不同的皮肤病变分割方法。第一种方法使用U-Nets，并引入基于直方图均衡的预处理步骤。第二种方法是基于C-Means聚类的方法，实现起来更简单，执行速度也更快。在算法输出和皮肤科医生的手分割图像之间的Jaccard指数被用来评估所提出的算法。尽管许多最近提出的深度神经网络来分割皮肤损伤需要大量的训练（即，具有GPU的计算机）的计算能力，但是本文的主要目的是提出可以仅与CPU一起使用的方法。例如，这严重限制了可以呈现给U-Net的训练实例的数量。比较两种算法，U-Nets比聚类方法实现了更高的Jaccard指数。此外，使用预处理步骤的直方图均衡化显着改善了U-Net分割结果。

##### URL
[https://arxiv.org/abs/1710.01248](https://arxiv.org/abs/1710.01248)

##### PDF
[https://arxiv.org/pdf/1710.01248](https://arxiv.org/pdf/1710.01248)

