---
layout: post
title: "Mixture of Counting CNNs: Adaptive Integration of CNNs Specialized to Specific Appearance for Crowd Counting"
date: 2017-03-28 03:41:44
categories: arXiv_CV
tags: arXiv_CV
author: Shohei Kumagai, Kazuhiro Hotta, Takio Kurita
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a crowd counting method. Crowd counting is difficult because of large appearance changes of a target which caused by density and scale changes. Conventional crowd counting methods generally utilize one predictor (e,g., regression and multi-class classifier). However, such only one predictor can not count targets with large appearance changes well. In this paper, we propose to predict the number of targets using multiple CNNs specialized to a specific appearance, and those CNNs are adaptively selected according to the appearance of a test image. By integrating the selected CNNs, the proposed method has the robustness to large appearance changes. In experiments, we confirm that the proposed method can count crowd with lower counting error than a CNN and integration of CNNs with fixed weights. Moreover, we confirm that each predictor automatically specialized to a specific appearance.

##### Abstract (translated by Google)
本文提出了一种人群统计方法。由于密度和尺度变化引起的目标的大的外观变化，人群计数是困难的。传统的人群计数方法通常使用一个预测器（例如，回归和多级分类器）。但是，只有一个预测因子不能很好地计算出外观变化大的目标。在本文中，我们建议使用专门针对特定外观的多个CNN来预测目标的数量，并且根据测试图像的外观来自适应地选择这些CNN。通过对选定的CNN进行整合，该方法对于大的外观变化具有鲁棒性。在实验中，我们确认所提出的方法可以计算比CNN有更低计数误差的人群以及具有固定权重的CNN的集成。而且，我们确认每个预测变量都自动专门针对特定的外观。

##### URL
[https://arxiv.org/abs/1703.09393](https://arxiv.org/abs/1703.09393)

##### PDF
[https://arxiv.org/pdf/1703.09393](https://arxiv.org/pdf/1703.09393)

