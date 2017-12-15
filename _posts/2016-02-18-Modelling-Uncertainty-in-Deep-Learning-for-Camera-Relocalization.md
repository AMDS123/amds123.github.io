---
layout: post
title: "Modelling Uncertainty in Deep Learning for Camera Relocalization"
date: 2016-02-18 13:30:25
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Alex Kendall, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
We present a robust and real-time monocular six degree of freedom visual relocalization system. We use a Bayesian convolutional neural network to regress the 6-DOF camera pose from a single RGB image. It is trained in an end-to-end manner with no need of additional engineering or graph optimisation. The algorithm can operate indoors and outdoors in real time, taking under 6ms to compute. It obtains approximately 2m and 6 degrees accuracy for very large scale outdoor scenes and 0.5m and 10 degrees accuracy indoors. Using a Bayesian convolutional neural network implementation we obtain an estimate of the model's relocalization uncertainty and improve state of the art localization accuracy on a large scale outdoor dataset. We leverage the uncertainty measure to estimate metric relocalization error and to detect the presence or absence of the scene in the input image. We show that the model's uncertainty is caused by images being dissimilar to the training dataset in either pose or appearance.

##### Abstract (translated by Google)
我们提出了一个强大的实时单目六自由度视觉再定位系统。我们使用贝叶斯卷积神经网络来从单个RGB图像回归6自由度摄像机姿态。它以端到端的方式进行训练，不需要额外的工程或图形优化。该算法可以实时在室内外进行操作，在6ms以内进行计算。对于大型户外场景，室内可获得约2米和6度的精度，在室内可获得0.5米和10度的精度。使用贝叶斯卷积神经网络实现，我们获得了对模型的重定位不确定性的估计，并改善了大规模户外数据集上的最新定位精度。我们利用不确定性度量来估计度量重定位误差，并检测输入图像中是否存在场景。我们表明，模型的不确定性是由图像与训练数据集在姿势或外观上不相似造成的。

##### URL
[https://arxiv.org/abs/1509.05909](https://arxiv.org/abs/1509.05909)

##### PDF
[https://arxiv.org/pdf/1509.05909](https://arxiv.org/pdf/1509.05909)

