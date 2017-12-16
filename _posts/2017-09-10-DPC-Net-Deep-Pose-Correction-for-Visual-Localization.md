---
layout: post
title: "DPC-Net: Deep Pose Correction for Visual Localization"
date: 2017-09-10 16:35:55
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Valentin Peretroukhin, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel method to fuse the power of deep networks with the computational efficiency of geometric and probabilistic localization algorithms. In contrast to other methods that completely replace a classical visual estimator with a deep network, we propose an approach that uses a convolutional neural network to learn difficult-to-model corrections to the estimator from ground-truth training data. To this end, we derive a novel loss function for learning SE(3) corrections based on a matrix Lie groups approach, with a natural formulation for balancing translation and rotation errors. We use this loss to train a Deep Pose Correction network (DPC-Net) that predicts corrections for a particular estimator, sensor and environment. Using the KITTI odometry dataset, we demonstrate significant improvements to the accuracy of a computationally-efficient sparse stereo visual odometry pipeline, that render it as accurate as a modern computationally-intensive dense estimator. Further, we show how DPC-Net can be used to mitigate the effect of poorly calibrated lens distortion parameters.

##### Abstract (translated by Google)
我们提出了一种融合深度网络的能力与几何和概率定位算法的计算效率的新方法。与其他方法完全取代了一个深度网络的经典视觉估计器，我们提出了一种方法，使用卷积神经网络来从地面实况训练数据学习估计的难以模型校正。为此，我们推导出一种基于矩阵李群方法学习SE（3）修正的新型损失函数，用自然的公式来平衡平移和旋转误差。我们使用这个损失来训练一个深度姿态修正网络（DPC-Net），该网络可以预测特定估计器，传感器和环境的修正。使用KITTI测距数据集，我们证明了计算效率较高的稀疏立体视觉测距流水线的准确性显着提高，使其与现代计算密集型估计器一样精确。此外，我们还展示了如何使用DPC-Net来减轻校准不佳的镜头失真参数的影响。

##### URL
[https://arxiv.org/abs/1709.03128](https://arxiv.org/abs/1709.03128)

##### PDF
[https://arxiv.org/pdf/1709.03128](https://arxiv.org/pdf/1709.03128)

