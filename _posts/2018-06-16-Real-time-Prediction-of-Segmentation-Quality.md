---
layout: post
title: "Real-time Prediction of Segmentation Quality"
date: 2018-06-16 13:53:31
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Deep_Learning Prediction
author: Robert Robinson, Ozan Oktay, Wenjia Bai, Vanya Valindria, Mihir Sanghvi, Nay Aung, Jos&#xe9; Paiva, Filip Zemrak, Kenneth Fung, Elena Lukaschuk, Aaron Lee, Valentina Carapella, Young Jin Kim, Bernhard Kainz, Stefan Piechnik, Stefan Neubauer, Steffen Petersen, Chris Page, Daniel Rueckert, Ben Glocker
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in deep learning based image segmentation methods have enabled real-time performance with human-level accuracy. However, occasionally even the best method fails due to low image quality, artifacts or unexpected behaviour of black box algorithms. Being able to predict segmentation quality in the absence of ground truth is of paramount importance in clinical practice, but also in large-scale studies to avoid the inclusion of invalid data in subsequent analysis. 
 In this work, we propose two approaches of real-time automated quality control for cardiovascular MR segmentations using deep learning. First, we train a neural network on 12,880 samples to predict Dice Similarity Coefficients (DSC) on a per-case basis. We report a mean average error (MAE) of 0.03 on 1,610 test samples and 97% binary classification accuracy for separating low and high quality segmentations. Secondly, in the scenario where no manually annotated data is available, we train a network to predict DSC scores from estimated quality obtained via a reverse testing strategy. We report an MAE=0.14 and 91% binary classification accuracy for this case. Predictions are obtained in real-time which, when combined with real-time segmentation methods, enables instant feedback on whether an acquired scan is analysable while the patient is still in the scanner. This further enables new applications of optimising image acquisition towards best possible analysis results.

##### Abstract (translated by Google)
基于深度学习的图像分割方法的最新进展已经实现了具有人类准确性的实时性能。然而，偶尔最好的方法也会由于低图像质量，伪像或黑箱算法的意外行为而失败。在缺乏基础事实的情况下能够预测分割质量在临床实践中是非常重要的，但在大规模研究中也是如此，以避免在随后的分析中包含无效数据。
 在这项工作中，我们提出了两种使用深度学习的心血管MR分割的实时自动质量控制方法。首先，我们对12,880个样本进行神经网络训练，根据每个案例预测Dice相似系数（DSC）。我们报告1,610个测试样本的平均误差（MAE）为0.03，分离低质量和高质量分段的二元分类准确率为97％。其次，在没有手动注释的数据可用的情况下，我们通过反向测试策略训练网络以预测质量来预测DSC分数。我们报告这种情况下MAE = 0.14和91％的二进制分类精度。预测是实时获得的，当与实时分割方法相结合时，能够即时反馈在病人仍在扫描仪中时所采集的扫描是否可分析。这进一步实现了优化图像采集的新应用，以实现最佳分析结果。

##### URL
[http://arxiv.org/abs/1806.06244](http://arxiv.org/abs/1806.06244)

##### PDF
[http://arxiv.org/pdf/1806.06244](http://arxiv.org/pdf/1806.06244)

