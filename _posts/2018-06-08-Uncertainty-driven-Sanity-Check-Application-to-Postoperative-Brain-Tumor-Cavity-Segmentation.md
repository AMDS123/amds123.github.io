---
layout: post
title: "Uncertainty-driven Sanity Check: Application to Postoperative Brain Tumor Cavity Segmentation"
date: 2018-06-08 12:09:39
categories: arXiv_CV
tags: arXiv_CV Review Segmentation CNN Deep_Learning Prediction
author: Alain Jungo, Raphael Meier, Ekin Ermis, Evelyn Herrmann, Mauricio Reyes
mathjax: true
---

* content
{:toc}

##### Abstract
Uncertainty estimates of modern neuronal networks provide additional information next to the computed predictions and are thus expected to improve the understanding of the underlying model. Reliable uncertainties are particularly interesting for safety-critical computer-assisted applications in medicine, e.g., neurosurgical interventions and radiotherapy planning. We propose an uncertainty-driven sanity check for the identification of segmentation results that need particular expert review. Our method uses a fully-convolutional neural network and computes uncertainty estimates by the principle of Monte Carlo dropout. We evaluate the performance of the proposed method on a clinical dataset with 30 postoperative brain tumor images. The method can segment the highly inhomogeneous resection cavities accurately (Dice coefficients 0.792 $\pm$ 0.154). Furthermore, the proposed sanity check is able to detect the worst segmentation and three out of the four outliers. The results highlight the potential of using the additional information from the model's parameter uncertainty to validate the segmentation performance of a deep learning model.

##### Abstract (translated by Google)
现代神经网络的不确定性估计提供了计算预测旁边的附加信息，因此有望提高对基础模型的理解。可靠的不确定性对于医学中安全关键的计算机辅助应用特别有用，例如神经外科干预和放射治疗计划。我们提出一个不确定性驱动的完整性检查来识别需要特定专家审查的分割结果。我们的方法使用全卷积神经网络，并根据蒙特卡罗丢失原理计算不确定性估计值。我们评估所提出的方法在30例术后脑肿瘤图像的临床数据集上的表现。该方法可以精确分割高度不均匀的切除空洞（Dice系数0.792 $ \ pm $ 0.154）。此外，所提出的完整性检查能够检测到最坏的分割，并且能够检测出四个异常值中的三个。结果突出显示了使用来自模型参数不确定性的附加信息来验证深度学习模型的分割性能的潜力。

##### URL
[http://arxiv.org/abs/1806.03106](http://arxiv.org/abs/1806.03106)

##### PDF
[http://arxiv.org/pdf/1806.03106](http://arxiv.org/pdf/1806.03106)

