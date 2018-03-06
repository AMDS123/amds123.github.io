---
layout: post
title: "Chest X-Ray Analysis of Tuberculosis by Deep Learning with Segmentation and Augmentation"
date: 2018-03-03 16:42:19
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Prediction
author: Sergii Stirenko, Yuriy Kochura, Oleg Alienin, Oleksandr Rokovyi, Peng Gang, Wei Zeng, Yuri Gordienko
mathjax: true
---

* content
{:toc}

##### Abstract
The results of chest X-ray (CXR) analysis of 2D images to get the statistically reliable predictions (availability of tuberculosis) by computer-aided diagnosis (CADx) on the basis of deep learning are presented. They demonstrate the efficiency of lung segmentation, lossless and lossy data augmentation for CADx of tuberculosis by deep convolutional neural network (CNN) applied to the small and not well-balanced dataset even. CNN demonstrates ability to train (despite overfitting) on the pre-processed dataset obtained after lung segmentation in contrast to the original not-segmented dataset. Lossless data augmentation of the segmented dataset leads to the lowest validation loss (without overfitting) and nearly the same accuracy (within the limits of standard deviation) in comparison to the original and other pre-processed datasets after lossy data augmentation. The additional limited lossy data augmentation results in the lower validation loss, but with a decrease of the validation accuracy. In conclusion, besides the more complex deep CNNs and bigger datasets, the better progress of CADx for the small and not well-balanced datasets even could be obtained by better segmentation, data augmentation, dataset stratification, and exclusion of non-evident outliers.

##### Abstract (translated by Google)
提供了基于深度学习的2D图像的胸部X射线（CXR）分析结果以通过计算机辅助诊断（CADx）获得统计上可靠的预测（结核病的可用性）。他们通过深卷积神经网络（CNN）证明肺部分割的效率，结核病CADx的无损和有损数据增加，甚至应用于小而不均衡的数据集。与原始未分段数据集相比，CNN展示了对肺分割后获得的预处理数据集进行训练（尽管过度拟合）的能力。与有损数据增强后的原始和其他预处理数据集相比，分段数据集的无损数据增强导致最低的验证损失（没有过拟合）和几乎相同的准确度（在标准偏差的范围内）。额外的有限有损数据增加会导致较低的验证损失，但会降低验证的准确性。总之，除了更复杂的深层CNN和更大的数据集之外，通过更好的分割，数据增强，数据集分层以及排除不明显的异常值，可以获得更小的，不均衡的数据集的更好CADx进展。

##### URL
[http://arxiv.org/abs/1803.01199](http://arxiv.org/abs/1803.01199)

##### PDF
[http://arxiv.org/pdf/1803.01199](http://arxiv.org/pdf/1803.01199)

