---
layout: post
title: "DPC-Net: Deep Pose Correction for Visual Localization"
date: 2018-09-10 01:36:08
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
我们提出了一种新方法，将深度网络的功率与几何和概率定位算法的计算效率融合在一起。与使用深度网络完全取代经典视觉估计器的其他方法相比，我们提出了一种方法，该方法使用卷积神经网络从地面实况训练数据中学习对估计器的难以模型的校正。为此，我们推导出一种新的损失函数，用于基于矩阵李群方法学习SE（3）校正，其具有用于平衡平移和旋转误差的自然公式。我们使用此损失来训练深度姿态校正网络（DPC-Net），该网络预测特定估计器，传感器和环境的校正。使用KITTI测距数据集，我们证明了计算效率稀疏立体视觉测距管道的准确性的显着改进，使其像现代计算密集型密集估计器一样准确。此外，我们展示了如何使用DPC-Net来减轻校准不良的镜头失真参数的影响。

##### URL
[http://arxiv.org/abs/1709.03128](http://arxiv.org/abs/1709.03128)

##### PDF
[http://arxiv.org/pdf/1709.03128](http://arxiv.org/pdf/1709.03128)

