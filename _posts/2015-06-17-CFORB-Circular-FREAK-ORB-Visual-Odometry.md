---
layout: post
title: "CFORB: Circular FREAK-ORB Visual Odometry"
date: 2015-06-17 09:44:42
categories: arXiv_CV
tags: arXiv_CV
author: Daniel J. Mankowitz, Ehud Rivlin
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel Visual Odometry algorithm entitled Circular FREAK-ORB (CFORB). This algorithm detects features using the well-known ORB algorithm [12] and computes feature descriptors using the FREAK algorithm [14]. CFORB is invariant to both rotation and scale changes, and is suitable for use in environments with uneven terrain. Two visual geometric constraints have been utilized in order to remove invalid feature descriptor matches. These constraints have not previously been utilized in a Visual Odometry algorithm. A variation to circular matching [16] has also been implemented. This allows features to be matched between images without having to be dependent upon the epipolar constraint. This algorithm has been run on the KITTI benchmark dataset and achieves a competitive average translational error of $3.73 \%$ and average rotational error of $0.0107 deg/m$. CFORB has also been run in an indoor environment and achieved an average translational error of $3.70 \%$. After running CFORB in a highly textured environment with an approximately uniform feature spread across the images, the algorithm achieves an average translational error of $2.4 \%$ and an average rotational error of $0.009 deg/m$.

##### Abstract (translated by Google)
我们提出了一个名为圆形FREAK-ORB（CFORB）的新颖的视觉内测算法。该算法使用众所周知的ORB算法[12]来检测特征，并使用FREAK算法来计算特征描述符[14]。 CFORB不受旋转和尺度变化的影响，适用于地形不平坦的环境。已经使用两个视觉几何约束来移除无效的特征描述符匹配。 Visual Odometry算法中以前没有使用这些约束。循环匹配[16]的变化也已经实现。这允许特征在图像之间匹配，而不必依赖于极线约束。该算法已经在KITTI基准数据集上运行，并且实现了$ 3.73 \％$的平均转换误差和$ 0.0107 deg / m $的平均转动误差。 CFORB也在室内运行，平均误差为3.70美元/％。在高度纹理化的环境中运行CFORB并在图像上散布大致均匀的特征之后，该算法实现了$ 2.4 \％$的平均平移误差和$ 0.009 deg / m $的平均旋转误差。

##### URL
[https://arxiv.org/abs/1506.05257](https://arxiv.org/abs/1506.05257)

##### PDF
[https://arxiv.org/pdf/1506.05257](https://arxiv.org/pdf/1506.05257)

