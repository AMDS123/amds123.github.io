---
layout: post
title: "Normalized Features for Improving the Generalization of DNN Based Speech Enhancement"
date: 2018-01-15 14:45:56
categories: arXiv_SD
tags: arXiv_SD Deep_Learning
author: Robert Rehr, Timo Gerkmann
mathjax: true
---

* content
{:toc}

##### Abstract
Enhancing noisy speech is an important task to restore its quality and to improve its intelligibility. In traditional non-machine-learning (ML) based approaches the parameters required for noise reduction are estimated blindly from the noisy observation while the actual filter functions are derived analytically based on statistical assumptions. Even though such approaches generalize well to many different acoustic conditions, the noise suppression capability in transient noises is low. To amend this shortcoming, machine-learning (ML) methods such as deep learning have been employed for speech enhancement. However, due to their data-driven nature, the generalization of ML based approaches to unknown noise types is still discussed. To improve the generalization of ML based algorithms and to enhance the noise suppression of non-ML based methods, we propose a combination of both approaches. For this, we employ the a priori signal-to-noise ratio (SNR) and the a posteriori SNR estimated as input features in a deep neural network (DNN) based enhancement scheme. We show that this approach allows ML based speech estimators to generalize quickly to unknown noise types even if only few noise conditions have been seen during training. Further, the proposed features outperform a competing approach where an estimate of the noise power spectral density is appended to the noisy spectra. Instrumental measures such as Perceptual Evaluation of Speech Quality (PESQ) and short-time objective intelligibility (STOI) indicate strong improvements in unseen conditions when the proposed features are used. Listening experiments confirm the improved generalization of our proposed combination.

##### Abstract (translated by Google)
提高语音噪音是恢复其质量和提高其可理解性的重要任务。在传统的基于非机器学习（ML）的方法中，噪声降低所需的参数是从噪声观测盲目估计的，而实际的滤波器函数是基于统计假设分析导出的。尽管这种方法很好地适用于许多不同的声学条件，但瞬态噪声中的噪声抑制能力较低。为了修正这个缺点，已经采用诸如深度学习的机器学习（ML）方法来进行语音增强。然而，由于其数据驱动的性质，仍然讨论基于ML的未知噪声类型方法的推广。为了改进基于ML的算法的泛化，并增强非基于ML的方法的噪声抑制，我们提出了两种方法的组合。为此，我们采用基于深度神经网络（DNN）的增强方案中的先验信噪比（SNR）和后验SNR作为输入特征进行估计。我们表明，这种方法允许基于ML的语音估计器快速推广到未知的噪声类型，即使在训练期间只有少量的噪声条件。此外，所提出的特征胜过竞争方法，其中噪声功率谱密度的估计被附加到噪声谱上。诸如语音质量感知评估（PESQ）和短时客观可理解性（STOI）等工具性措施表明，当使用提议的特征时，看不见的情况有很大的改善。听力实验证实了我们提出的组合的改进的泛化。

##### URL
[http://arxiv.org/abs/1709.02175](http://arxiv.org/abs/1709.02175)

##### PDF
[http://arxiv.org/pdf/1709.02175](http://arxiv.org/pdf/1709.02175)

