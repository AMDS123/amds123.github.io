---
layout: post
title: "Superhuman Accuracy on the SNEMI3D Connectomics Challenge"
date: 2017-05-31 23:19:37
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Kisuk Lee, Jonathan Zung, Peter Li, Viren Jain, H. Sebastian Seung
mathjax: true
---

* content
{:toc}

##### Abstract
For the past decade, convolutional networks have been used for 3D reconstruction of neurons from electron microscopic (EM) brain images. Recent years have seen great improvements in accuracy, as evidenced by submissions to the SNEMI3D benchmark challenge. Here we report the first submission to surpass the estimate of human accuracy provided by the SNEMI3D leaderboard. A variant of 3D U-Net is trained on a primary task of predicting affinities between nearest neighbor voxels, and an auxiliary task of predicting long-range affinities. The training data is augmented by simulated image defects. The nearest neighbor affinities are used to create an oversegmentation, and then supervoxels are greedily agglomerated based on mean affinity. The resulting SNEMI3D score exceeds the estimate of human accuracy by a large margin. While one should be cautious about extrapolating from the SNEMI3D benchmark to real-world accuracy of large-scale neural circuit reconstruction, our result inspires optimism that the goal of full automation may be realizable in the future.

##### Abstract (translated by Google)
在过去十年中，卷积网络已经被用于从电子显微镜（EM）脑图像的神经元的三维重建。近年来，SNEMI3D基准测试挑战的提交就证明了准确度有了很大提高。在这里，我们报告第一次提交超过SNEMI3D排行榜提供的人类准确度的估计。 3D U-Net的一个变体是训练预测最近邻元素之间的亲和性的主要任务，以及预测远程亲和性的辅助任务。训练数据通过模拟图像缺陷来增强。最近邻居的亲和力被用来创造一个超级规模，然后supervoxels贪婪集聚的基础上的平均亲和力。由此产生的SNEMI3D得分大大超出了人类精确度的估计。尽管从SNEMI3D基准测试推导到大规模神经电路重构的实际精度，我们应该保持谨慎，但我们的结果激发了人们乐观的态度，认为未来可以实现全自动化的目标。

##### URL
[https://arxiv.org/abs/1706.00120](https://arxiv.org/abs/1706.00120)

##### PDF
[https://arxiv.org/pdf/1706.00120](https://arxiv.org/pdf/1706.00120)

