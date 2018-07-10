---
layout: post
title: "DeepSource: Point Source Detection using Deep Learning"
date: 2018-07-07 18:00:07
categories: arXiv_CV
tags: arXiv_CV Survey CNN Deep_Learning Detection
author: A. Vafaei Sadr, Etienne. E. Vos, Bruce A. Bassett, Zafiirah Hosenie, N. Oozeer, Michelle Lochner
mathjax: true
---

* content
{:toc}

##### Abstract
Point source detection at low signal-to-noise is challenging for astronomical surveys, particularly in radio interferometry images where the noise is correlated. Machine learning is a promising solution, allowing the development of algorithms tailored to specific telescope arrays and science cases. We present DeepSource - a deep learning solution - that uses convolutional neural networks to achieve these goals. DeepSource enhances the Signal-to-Noise Ratio (SNR) of the original map and then uses dynamic blob detection to detect sources. Trained and tested on two sets of 500 simulated 1 deg x 1 deg MeerKAT images with a total of 300,000 sources, DeepSource is essentially perfect in both purity and completeness down to SNR = 4 and outperforms PyBDSF in all metrics. For uniformly-weighted images it achieves a Purity x Completeness (PC) score at SNR = 3 of 0.73, compared to 0.31 for the best PyBDSF model. For natural-weighting we find a smaller improvement of ~40% in the PC score at SNR = 3. If instead we ask where either of the purity or completeness first drop to 90%, we find that DeepSource reaches this value at SNR = 3.6 compared to the 4.3 of PyBDSF (natural-weighting). A key advantage of DeepSource is that it can learn to optimally trade off purity and completeness for any science case under consideration. Our results show that deep learning is a promising approach to point source detection in astronomical images.

##### Abstract (translated by Google)
低信噪比的点源检测对于天文测量来说是一项挑战，特别是在噪声相关的无线电干涉测量图像中。机器学习是一种很有前途的解决方案，允许开发针对特定望远镜阵列和科学案例的算法。我们提出DeepSource--一种深度学习解决方案 - 使用卷积神经网络来实现这些目标。 DeepSource增强了原始地图的信噪比（SNR），然后使用动态斑点检测来检测源。经过两组500个模拟1度x 1度MeerKAT图像的训练和测试，共有300,000个源，DeepSource在纯度和完整性方面都非常完美，低至SNR = 4，并且在所有指标中都优于PyBDSF。对于均匀加权的图像，它在SNR = 3时达到0.73的纯度x完整性（PC）分数，而最佳PyBDSF模型的分数为0.31。对于自然加权，我们发现在SNR = 3时，PC得分的改善幅度较小，约为40％。相反，我们要求在纯度或完整性首先降至90％时，我们发现DeepSource在SNR = 3.6时达到此值与PyBDSF的4.3（自然加权）相比。 DeepSource的一个关键优势是它可以学习如何以最佳方式权衡所考虑的任何科学案例的纯度和完整性。我们的研究结果表明，深度学习是天文图像中点源检测的一种有前景的方法。

##### URL
[http://arxiv.org/abs/1807.02701](http://arxiv.org/abs/1807.02701)

##### PDF
[http://arxiv.org/pdf/1807.02701](http://arxiv.org/pdf/1807.02701)

