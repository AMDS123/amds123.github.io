---
layout: post
title: "CNN-SLAM: Real-time dense monocular SLAM with learned depth prediction"
date: 2017-04-11 18:37:11
categories: arXiv_CV
tags: arXiv_CV CNN Prediction SLAM
author: Keisuke Tateno, Federico Tombari, Iro Laina, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
Given the recent advances in depth prediction from Convolutional Neural Networks (CNNs), this paper investigates how predicted depth maps from a deep neural network can be deployed for accurate and dense monocular reconstruction. We propose a method where CNN-predicted dense depth maps are naturally fused together with depth measurements obtained from direct monocular SLAM. Our fusion scheme privileges depth prediction in image locations where monocular SLAM approaches tend to fail, e.g. along low-textured regions, and vice-versa. We demonstrate the use of depth prediction for estimating the absolute scale of the reconstruction, hence overcoming one of the major limitations of monocular SLAM. Finally, we propose a framework to efficiently fuse semantic labels, obtained from a single frame, with dense SLAM, yielding semantically coherent scene reconstruction from a single view. Evaluation results on two benchmark datasets show the robustness and accuracy of our approach.

##### Abstract (translated by Google)
鉴于卷积神经网络（CNN）在深度预测方面的最新进展，本文研究了深度神经网络预测深度图如何能够用于精确和致密的单眼重建。我们提出一种方法，CNN预测的密集深度图自然地与直接单目SLAM获得的深度测量结合在一起。我们的融合方案在单眼SLAM方法倾向于失败的图像位置中授予深度预测，例如，沿着低纹理区域，反之亦然。我们展示了使用深度预测来估计重建的绝对尺度，从而克服了单眼SLAM的一个主要局限性。最后，我们提出了一个框架，以有效融合从单个框架获得的语义标签与稠密的SLAM，从单个视图产生语义上相关的场景重建。两个基准数据集的评估结果显示了我们方法的稳健性和准确性。

##### URL
[https://arxiv.org/abs/1704.03489](https://arxiv.org/abs/1704.03489)

##### PDF
[https://arxiv.org/pdf/1704.03489](https://arxiv.org/pdf/1704.03489)

