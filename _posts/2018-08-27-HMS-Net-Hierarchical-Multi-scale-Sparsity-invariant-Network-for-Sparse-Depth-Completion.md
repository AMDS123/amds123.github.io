---
layout: post
title: "HMS-Net: Hierarchical Multi-scale Sparsity-invariant Network for Sparse Depth Completion"
date: 2018-08-27 04:43:34
categories: arXiv_CV
tags: arXiv_CV Review Sparse Attention
author: Zixuan Huang, Junming Fan, Shuai Yi, Xiaogang Wang, Hongsheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Dense depth cues are important and have wide applications in various computer vision tasks. In autonomous driving, LIDAR sensors are adopted to acquire depth measurements around the vehicle to perceive the surrounding environments. However, depth maps obtained by LIDAR are generally sparse because of its hardware limitation. The task of depth completion attracts increasing attention, which aims at generating a dense depth map from an input sparse depth map. To effectively utilize multi-scale features, we propose three novel sparsity-invariant operations, based on which, a sparsity-invariant multi-scale encoder-decoder network (HMS-Net) for handling sparse inputs and sparse feature maps is also proposed. Additional RGB features could be incorporated to further improve the depth completion performance. Our extensive experiments and component analysis on two public benchmarks, KITTI depth completion benchmark and NYU-depth-v2 dataset, demonstrate the effectiveness of the proposed approach. As of Aug. 12th, 2018, on KITTI depth completion leaderboard, our proposed model without RGB guidance ranks first among all peer-reviewed methods without using RGB information, and our model with RGB guidance ranks second among all RGB-guided methods.

##### Abstract (translated by Google)
密集的深度线索很重要，并且在各种计算机视觉任务中具有广泛的应用。在自动驾驶中，采用LIDAR传感器来获取车辆周围的深度测量值以感知周围环境。然而，由于其硬件限制，LIDAR获得的深度图通常是稀疏的。深度完成的任务吸引了越来越多的注意力，其目的在于从输入稀疏深度图生成密集的深度图。为了有效地利用多尺度特征，我们提出了三种新的稀疏不变运算，在此基础上，还提出了一种稀疏度不变的多尺度编码器 - 解码器网络（HMS-Net），用于处理稀疏输入和稀疏特征映射。可以结合额外的RGB特征以进一步改善深度完成性能。我们对两个公共基准，KITTI深度完成基准和NYU-depth-v2数据集的广泛实验和成分分析证明了该方法的有效性。截至2018年8月12日，在KITTI深度完成排行榜上，我们提出的没有RGB引导的模型在所有同行评审方法中排名第一，而不使用RGB信息，我们的RGB引导模型在所有RGB引导方法中排名第二。

##### URL
[http://arxiv.org/abs/1808.08685](http://arxiv.org/abs/1808.08685)

##### PDF
[http://arxiv.org/pdf/1808.08685](http://arxiv.org/pdf/1808.08685)

