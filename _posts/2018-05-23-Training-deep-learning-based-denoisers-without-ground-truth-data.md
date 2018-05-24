---
layout: post
title: "Training deep learning based denoisers without ground truth data"
date: 2018-05-23 08:23:32
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Shakarim Soltanayev, Se Young Chun
mathjax: true
---

* content
{:toc}

##### Abstract
Recent deep learning based denoisers often outperform state-of-the-art conventional denoisers such as BM3D. They are typically trained to minimize the mean squared error (MSE) between the output of a deep neural network and the ground truth image. In deep learning based denoisers, it is important to use high quality noiseless ground truth for high performance, but it is often challenging or even infeasible to obtain such a clean image in application areas such as hyperspectral remote sensing and medical imaging. We propose a Stein's Unbiased Risk Estimator (SURE) based method for training deep neural network denoisers only with noisy images. We demonstrated that our SURE based method without ground truth was able to train deep neural network denoisers to yield performance close to deep learning denoisers trained with ground truth and to outperform state-of-the-art BM3D. Further improvements were achieved by including noisy test images for training denoiser networks using our proposed SURE based method.

##### Abstract (translated by Google)
最近，基于深度学习的分析器常常比最先进的传统分析器（例如BM3D）更胜一筹。它们通常经过训练以最小化深层神经网络输出与地面实况图像之间的均方误差（MSE）。在基于深度学习的分解器中，为高性能使用高质量的无噪声基本事实非常重要，但在高光谱遥感和医学成像等应用领域获得如此清晰的图像通常是具有挑战性的，甚至是不可行的。我们提出了一种基于Stein's无偏风险估计器（SURE）的方法，仅用于噪声图像训练深度神经网络分解器。我们证明了我们基于SURE的没有基础事实的方法能够训练深度神经网络分解器来产生接近深度学习分解器的性能，这些深入学习分解器用基础事实进行训练并且超越了最先进的BM3D。通过使用我们提出的基于SURE的方法将训练降噪网络的噪声测试图像包含进来，实现了进一步的改进。

##### URL
[http://arxiv.org/abs/1803.01314](http://arxiv.org/abs/1803.01314)

##### PDF
[http://arxiv.org/pdf/1803.01314](http://arxiv.org/pdf/1803.01314)

