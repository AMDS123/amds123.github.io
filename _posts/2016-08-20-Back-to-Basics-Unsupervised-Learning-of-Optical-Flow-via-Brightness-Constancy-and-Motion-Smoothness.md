---
layout: post
title: "Back to Basics: Unsupervised Learning of Optical Flow via Brightness Constancy and Motion Smoothness"
date: 2016-08-20 15:25:31
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jason J. Yu, Adam W. Harley, Konstantinos G. Derpanis
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, convolutional networks (convnets) have proven useful for predicting optical flow. Much of this success is predicated on the availability of large datasets that require expensive and involved data acquisition and laborious la- beling. To bypass these challenges, we propose an unsuper- vised approach (i.e., without leveraging groundtruth flow) to train a convnet end-to-end for predicting optical flow be- tween two images. We use a loss function that combines a data term that measures photometric constancy over time with a spatial term that models the expected variation of flow across the image. Together these losses form a proxy measure for losses based on the groundtruth flow. Empiri- cally, we show that a strong convnet baseline trained with the proposed unsupervised approach outperforms the same network trained with supervision on the KITTI dataset.

##### Abstract (translated by Google)
最近，卷积网络（convnets）已被证明可用于预测光流。这种成功的大部分是基于大数据集的可用性，这些大数据集需要昂贵且涉及的数据采集和费力的流程。为了避开这些挑战，我们提出了一个没有经验的方法（即，不利用地面真实流动）来端到端地训练一个小圆点来预测两幅图像之间的光流。我们使用一个损失函数，结合了一个数据项，测量光度恒定随着时间的推移与一个空间项，模拟预期的变化的图像流量。这些损失合在一起形成了基于地面真实流量的损失的替代指标。经验地说，我们表明，用无监督方法提出的一个强大的基线基线胜过了KITTI数据集监督下训练的同一个网络。

##### URL
[https://arxiv.org/abs/1608.05842](https://arxiv.org/abs/1608.05842)

##### PDF
[https://arxiv.org/pdf/1608.05842](https://arxiv.org/pdf/1608.05842)

