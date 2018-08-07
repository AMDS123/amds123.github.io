---
layout: post
title: "Learning to Align Images using Weak Geometric Supervision"
date: 2018-08-04 04:28:52
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised CNN
author: Jing Dong, Byron Boots, Frank Dellaert, Ranveer Chandra, Sudipta N. Sinha
mathjax: true
---

* content
{:toc}

##### Abstract
Image alignment tasks require accurate pixel correspondences, which are usually recovered by matching local feature descriptors. Such descriptors are often derived using supervised learning on existing datasets with ground truth correspondences. However, the cost of creating such datasets is usually prohibitive. In this paper, we propose a new approach to align two images related by an unknown 2D homography where the local descriptor is learned from scratch from the images and the homography is estimated simultaneously. Our key insight is that a siamese convolutional neural network can be trained jointly while iteratively updating the homography parameters by optimizing a single loss function. Our method is currently weakly supervised because the input images need to be roughly aligned. We have used this method to align images of different modalities such as RGB and near-infra-red (NIR) without using any prior labeled data. Images automatically aligned by our method were then used to train descriptors that generalize to new images. We also evaluated our method on RGB images. On the HPatches benchmark, our method achieves comparable accuracy to deep local descriptors that were trained offline in a supervised setting.

##### Abstract (translated by Google)
图像对齐任务需要精确的像素对应，通常通过匹配局部特征描述符来恢复。这些描述符通常使用具有地面真实对应的现有数据集的监督学习来导出。但是，创建此类数据集的成本通常过高。在本文中，我们提出了一种新的方法来对齐由未知的二维单应性相关的两个图像，其中从图像中从头开始学习局部描述符并同时估计单应性。我们的关键见解是，可以联合训练暹罗卷积神经网络，同时通过优化单个损失函数迭代地更新单应性参数。我们的方法目前受到弱监督，因为输入图像需要大致对齐。我们已经使用这种方法来对齐不同模态的图像，例如RGB和近红外（NIR），而不使用任何先前标记的数据。然后使用我们的方法自动对齐的图像来训练对新图像进行推广的描述符。我们还评估了RGB图像的方法。在HPatches基准测试中，我们的方法实现了与在监督环境中离线训练的深度局部描述符相当的精度。

##### URL
[https://arxiv.org/abs/1808.01424](https://arxiv.org/abs/1808.01424)

##### PDF
[https://arxiv.org/pdf/1808.01424](https://arxiv.org/pdf/1808.01424)

