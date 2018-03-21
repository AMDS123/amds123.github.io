---
layout: post
title: "Self-Supervised Monocular Image Depth Learning and Confidence Estimation"
date: 2018-03-14 22:59:01
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Long Chen, Wen Tang, Nigel John
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) need large amounts of data with ground truth annotation, which is a challenging problem that has limited the development and fast deployment of CNNs for many computer vision tasks. We propose a novel framework for depth estimation from monocular images with corresponding confidence in a self-supervised manner. A fully differential patch-based cost function is proposed by using the Zero-Mean Normalized Cross Correlation (ZNCC) that takes multi-scale patches as a matching strategy. This approach greatly increases the accuracy and robustness of the depth learning. In addition, the proposed patch-based cost function can provide a 0 to 1 confidence, which is then used to supervise the training of a parallel network for confidence map learning and estimation. Evaluation on KITTI dataset shows that our method outperforms the state-of-the-art results.

##### Abstract (translated by Google)
卷积神经网络（CNN）需要大量的具有地面真实注释的数据，这是一个具有挑战性的问题，它限制了许多计算机视觉任务的CNNs的开发和快速部署。我们提出了一种新颖的基于单目图像的深度估计框架，并且具有相应的自我监督方式的信心。基于零均值归一化互相关（ZNCC）提出了一种全差分基于块的成本函数，该算法将多尺度贴片作为匹配策略。这种方法大大提高了深度学习的准确性和鲁棒性。此外，所提出的基于补丁的成本函数可以提供0到1的置信度，然后用它来监督并行网络的训练以进行置信度学习和估计。对KITTI数据集的评估表明，我们的方法胜过了最先进的结果。

##### URL
[https://arxiv.org/abs/1803.05530](https://arxiv.org/abs/1803.05530)

##### PDF
[https://arxiv.org/pdf/1803.05530](https://arxiv.org/pdf/1803.05530)

