---
layout: post
title: "Detecting and Correcting for Label Shift with Black Box Predictors"
date: 2018-02-12 07:16:03
categories: arXiv_AI
tags: arXiv_AI Face Prediction
author: Zachary C. Lipton, Yu-Xiang Wang, Alex Smola
mathjax: true
---

* content
{:toc}

##### Abstract
Faced with distribution shift between training and test set, we wish to detect and quantify the shift, and to correct our classifiers without test set labels. Motivated by medical diagnosis, where diseases (targets), cause symptoms (observations), we focus on label shift, where the label marginal $p(y)$ changes but the conditional $p(x|y)$ does not. We propose Black Box Shift Estimation (BBSE) to estimate the test distribution $p(y)$. BBSE exploits arbitrary black box predictors to reduce dimensionality prior to shift correction. While better predictors give tighter estimates, BBSE works even when predictors are biased, inaccurate, or uncalibrated, so long as their confusion matrices are invertible. We prove BBSE's consistency, bound its error, and introduce a statistical test that uses BBSE to detect shift. We also leverage BBSE to correct classifiers. Experiments demonstrate accurate estimates and improved prediction, even on high-dimensional datasets of natural images

##### Abstract (translated by Google)
面对训练和测试集之间的分布转换，我们希望检测和量化转换，并在没有测试集标签的情况下纠正我们的分类器。受疾病（目标），导致症状（观察）的医学诊断的驱动，我们关注标签移位，其中标签边际$ p（y）$发生变化，但条件$ p（x | y）$没有变化。我们提出黑盒移位估计（BBSE）来估计测试分布$ p（y）$。 BBSE利用任意的黑匣子预测器来降低偏移校正之前的维度。尽管更好的预测因子给出了更加严格的估计值，但即使预测因子有偏差，不准确或未经校准，BBSE也能起作用，只要它们的混淆矩阵是可逆的。我们证明了BBSE的一致性，限制了它的错误，并引入了一个使用BBSE来检测转变的统计测试。我们还利用BBSE来纠正分类器。即使在自然图像的高维数据集上，实验也可以证明准确的估计和改进的预测

##### URL
[http://arxiv.org/abs/1802.03916](http://arxiv.org/abs/1802.03916)

##### PDF
[http://arxiv.org/pdf/1802.03916](http://arxiv.org/pdf/1802.03916)

