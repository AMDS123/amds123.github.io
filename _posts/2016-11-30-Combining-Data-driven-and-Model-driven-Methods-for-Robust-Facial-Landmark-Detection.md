---
layout: post
title: "Combining Data-driven and Model-driven Methods for Robust Facial Landmark Detection"
date: 2016-11-30 14:01:45
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Detection
author: Hongwen Zhang, Qi Li, Zhenan Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Facial landmark detection is an important but challenging task for real-world computer vision applications. This paper proposes an accurate and robust approach for facial landmark detection by combining data-driven and model-driven methods. Firstly, a fully convolutional network (FCN) is trained to generate response maps of all facial landmark points. Such a data-driven method can make full use of holistic information in a facial image for global estimation of facial landmarks. Secondly, the maximum points in the response maps are fitted with a pre-trained point distribution model (PDM) to generate initial facial landmark shape. Such a model-driven method can correct the location errors of outliers by considering shape prior information. Thirdly, a weighted version of Regularized Landmark Mean-Shift (RLMS) is proposed to fine-tune facial landmark shapes iteratively. The weighting strategy is based on the confidence of convolutional response maps so that FCN is integrated into the framework of Constrained Local Model (CLM). Such an Estimation-Correction-Tuning process perfectly combines the global robustness advantage of data-driven method (FCN), outlier correction advantage of model-driven method (PDM) and non-parametric optimization advantage of RLMS. The experimental results demonstrate that the proposed approach outperforms state-of-the-art solutions on the 300-W dataset. Our approach is well-suited for face images with large poses, exaggerated expression, and occlusions.

##### Abstract (translated by Google)
对于真实世界的计算机视觉应用来说，面部标志检测是一项重要而又具有挑战性的任务本文结合数据驱动方法和模型驱动方法，提出了一种精确，鲁棒的面部标志检测方法。首先，完全卷积网络（FCN）被训练以生成所有面部标志点的响应图。这种数据驱动的方法可以充分利用面部图像中的整体信息进行面部标志的全局估计。其次，将响应图中的最大点与预先训练的点分布模型（PDM）进行拟合，以生成初始的面部标志形状。这种模型驱动的方法可以通过考虑形状先验信息来纠正异常值的位置误差。再次，提出了一个加权版本的规则化地标均值漂移（RLMS）来迭代地微调面部标志形状。加权策略是基于卷积响应映射的置信度，从而将FCN集成到约束局部模型（CLM）框架中。这种估计校正调整过程完美地结合了数据驱动方法（FCN）的全局鲁棒性优势，模型驱动方法（PDM）的异常校正优点和RLMS的非参数优化优势。实验结果表明，所提出的方法胜过了300-W数据集上最先进的解决方案。我们的方法非常适合具有大姿势，夸张的表情和遮挡的脸部图像。

##### URL
[https://arxiv.org/abs/1611.10152](https://arxiv.org/abs/1611.10152)

##### PDF
[https://arxiv.org/pdf/1611.10152](https://arxiv.org/pdf/1611.10152)

