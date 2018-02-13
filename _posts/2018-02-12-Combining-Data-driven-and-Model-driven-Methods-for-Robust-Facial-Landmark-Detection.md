---
layout: post
title: "Combining Data-driven and Model-driven Methods for Robust Facial Landmark Detection"
date: 2018-02-12 03:03:59
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Detection
author: Hongwen Zhang, Qi Li, Zhenan Sun, Yunfan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Facial landmark detection is an important yet challenging task for real-world computer vision applications. This paper proposes an effective and robust approach for facial landmark detection by combining data- and model-driven methods. Firstly, a Fully Convolutional Network (FCN) is trained to compute response maps of all facial landmark points. Such a data-driven method could make full use of holistic information in a facial image for global estimation of facial landmarks. After that, the maximum points in the response maps are fitted with a pre-trained Point Distribution Model (PDM) to generate the initial facial shape. This model-driven method is able to correct the inaccurate locations of outliers by considering the shape prior information. Finally, a weighted version of Regularized Landmark Mean-Shift (RLMS) is employed to fine-tune the facial shape iteratively. This Estimation-Correction-Tuning process perfectly combines the advantages of the global robustness of data-driven method (FCN), outlier correction capability of model-driven method (PDM) and non-parametric optimization of RLMS. Results of extensive experiments demonstrate that our approach achieves state-of-the-art performances on challenging datasets including 300W, AFLW, AFW and COFW. The proposed method is able to produce satisfying detection results on face images with exaggerated expressions, large head poses, and partial occlusions.

##### Abstract (translated by Google)
面部标志物检测对于真实世界的计算机视觉应用来说是一项重要且具有挑战性的任务本文通过结合数据和模型驱动方法提出了一种有效且稳健的面部标志检测方法。首先，完全卷积网络（FCN）被训练以计算所有面部标志点的响应图。这种数据驱动的方法可以充分利用面部图像中的整体信息进行面部地标的全局估计。之后，响应图中的最大点与预先训练的点分布模型（PDM）进行拟合以生成初始面部形状。这种模型驱动的方法能够通过考虑形状先验信息来校正异常值的不准确位置。最后，采用加权版本的正则化地标均值漂移（RLMS）来迭代地微调面部形状。这种估计校正调整过程完美结合了数据驱动方法（FCN）的全局鲁棒性，模型驱动方法（PDM）的异常校正能力和RLMS的非参数优化的优点。大量实验的结果表明，我们的方法在包括300W，AFLW，AFW和COFW在内的具有挑战性的数据集上实现了最先进的性能。该方法能够在夸大表情，大头姿势和局部遮挡的情况下，对人脸图像产生满意的检测结果。

##### URL
[http://arxiv.org/abs/1611.10152](http://arxiv.org/abs/1611.10152)

##### PDF
[http://arxiv.org/pdf/1611.10152](http://arxiv.org/pdf/1611.10152)

