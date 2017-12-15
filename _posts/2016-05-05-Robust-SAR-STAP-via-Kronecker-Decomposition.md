---
layout: post
title: "Robust SAR STAP via Kronecker Decomposition"
date: 2016-05-05 23:53:32
categories: arXiv_CV
tags: arXiv_CV Detection
author: Kristjan Greenewald, Edmund Zelnio, Alfred Hero
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a spatio-temporal decomposition for the detection of moving targets in multiantenna SAR. As a high resolution radar imaging modality, SAR detects and localizes non-moving targets accurately, giving it an advantage over lower resolution GMTI radars. Moving target detection is more challenging due to target smearing and masking by clutter. Space-time adaptive processing (STAP) is often used to remove the stationary clutter and enhance the moving targets. In this work, it is shown that the performance of STAP can be improved by modeling the clutter covariance as a space vs. time Kronecker product with low rank factors. Based on this model, a low-rank Kronecker product covariance estimation algorithm is proposed, and a novel separable clutter cancelation filter based on the Kronecker covariance estimate is introduced. The proposed method provides orders of magnitude reduction in the required number of training samples, as well as improved robustness to corruption of the training data. Simulation results and experiments using the Gotcha SAR GMTI challenge dataset are presented that confirm the advantages of our approach relative to existing techniques.

##### Abstract (translated by Google)
本文提出了一种多天线SAR中运动目标检测的时空分解算法。作为一种高分辨率的雷达成像模式，SAR能够精确地检测和定位非移动目标，与低分辨率的GMTI雷达相比具有优势。移动目标检测由于目标涂抹和杂波掩蔽而更具挑战性。空时自适应处理（STAP）经常被用来去除固定的杂波和增强运动目标。在这项工作中，显示STAP的性能可以通过将杂波协方差建模为具有低秩因子的空间对时间克罗内克（Kronecker）产品来改进。在此模型基础上，提出了一种低秩克罗内克乘积协方差估计算法，并引入基于克罗内克协方差估计的新型可分离杂波消除滤波器。所提出的方法在所需数量的训练样本中提供了数量级的减少，并且改善了对训练数据的破坏的鲁棒性。仿真结果和使用Gotcha SAR GMTI挑战数据集的实验证明了我们的方法相对于现有技术的优势。

##### URL
[https://arxiv.org/abs/1605.01790](https://arxiv.org/abs/1605.01790)

##### PDF
[https://arxiv.org/pdf/1605.01790](https://arxiv.org/pdf/1605.01790)

