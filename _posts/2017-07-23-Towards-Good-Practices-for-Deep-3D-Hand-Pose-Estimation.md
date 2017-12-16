---
layout: post
title: "Towards Good Practices for Deep 3D Hand Pose Estimation"
date: 2017-07-23 05:14:31
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Detection
author: Hengkai Guo, Guijin Wang, Xinghao Chen, Cairong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
3D hand pose estimation from single depth image is an important and challenging problem for human-computer interaction. Recently deep convolutional networks (ConvNet) with sophisticated design have been employed to address it, but the improvement over traditional random forest based methods is not so apparent. To exploit the good practice and promote the performance for hand pose estimation, we propose a tree-structured Region Ensemble Network (REN) for directly 3D coordinate regression. It first partitions the last convolution outputs of ConvNet into several grid regions. The results from separate fully-connected (FC) regressors on each regions are then integrated by another FC layer to perform the estimation. By exploitation of several training strategies including data augmentation and smooth $L_1$ loss, proposed REN can significantly improve the performance of ConvNet to localize hand joints. The experimental results demonstrate that our approach achieves the best performance among state-of-the-art algorithms on three public hand pose datasets. We also experiment our methods on fingertip detection and human pose datasets and obtain state-of-the-art accuracy.

##### Abstract (translated by Google)
单一深度图像的3D手势估计是人机交互的重要和挑战性问题。最近采用了复杂设计的深度卷积网络（ConvNet）来解决这个问题，但是相对传统的随机森林方法的改进并不明显。为了充分利用这种良好的实践手段，提高手部姿态估计的性能，本文提出了一种用于直接三维坐标回归的树状结构区域集成网络（REN）。它首先将ConvNet的最后卷积输出分成几个网格区域。然后将每个区域的单独完全连接（FC）回归器的结果由另一FC层整合以进行估计。通过利用包括数据增加和平滑$ L_1 $损失在内的多种培训策略，REN可以显着提高ConvNet对手关节定位的性能。实验结果表明，我们的方法在三个公共手部姿态数据集上的最新算法中达到最佳性能。我们还试验了我们的指尖检测方法和人体姿态数据集，并获得了最新的精度。

##### URL
[https://arxiv.org/abs/1707.07248](https://arxiv.org/abs/1707.07248)

##### PDF
[https://arxiv.org/pdf/1707.07248](https://arxiv.org/pdf/1707.07248)

