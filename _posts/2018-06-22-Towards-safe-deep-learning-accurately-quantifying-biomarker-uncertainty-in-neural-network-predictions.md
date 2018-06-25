---
layout: post
title: "Towards safe deep learning: accurately quantifying biomarker uncertainty in neural network predictions"
date: 2018-06-22 12:54:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning Prediction
author: Zach Eaton-Rosen, Felix Bragman, Sotirios Bisdas, Sebastien Ourselin, M. Jorge Cardoso
mathjax: true
---

* content
{:toc}

##### Abstract
Automated medical image segmentation, specifically using deep learning, has shown outstanding performance in semantic segmentation tasks. However, these methods rarely quantify their uncertainty, which may lead to errors in downstream analysis. In this work we propose to use Bayesian neural networks to quantify uncertainty within the domain of semantic segmentation. We also propose a method to convert voxel-wise segmentation uncertainty into volumetric uncertainty, and calibrate the accuracy and reliability of confidence intervals of derived measurements. When applied to a tumour volume estimation application, we demonstrate that by using such modelling of uncertainty, deep learning systems can be made to report volume estimates with well-calibrated error-bars, making them safer for clinical use. We also show that the uncertainty estimates extrapolate to unseen data, and that the confidence intervals are robust in the presence of artificial noise. This could be used to provide a form of quality control and quality assurance, and may permit further adoption of deep learning tools in the clinic.

##### Abstract (translated by Google)
自动医学图像分割，特别是使用深度学习，在语义分割任务中表现出色。然而，这些方法很少量化它们的不确定性，这可能导致下游分析中的错误。在这项工作中，我们建议使用贝叶斯神经网络来量化语义分割领域内的不确定性。我们还提出了一种将基于体素的分割不确定性转换为体积不确定性的方法，并校准了派生测量的置信区间的准确性和可靠性。当应用于肿瘤体积估算应用时，我们证明通过使用这种不确定性建模，可以使用深度学习系统通过校准良好的误差棒报告体积估计，使其在临床使用时更安全。我们还表明，不确定性估计推断为看不见的数据，并且在存在人为噪声的情况下置信区间是稳健的。这可以用来提供一种质量控制和质量保证的形式，并且可以允许在诊所中进一步采用深度学习工具。

##### URL
[http://arxiv.org/abs/1806.08640](http://arxiv.org/abs/1806.08640)

##### PDF
[http://arxiv.org/pdf/1806.08640](http://arxiv.org/pdf/1806.08640)

