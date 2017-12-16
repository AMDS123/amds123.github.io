---
layout: post
title: "Deep Poincare Map For Robust Medical Image Segmentation"
date: 2017-03-27 17:37:33
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Yuanhan Mo, Fangde Liu, Jingqing Zhang, Guang Yang, Taigang He, Yike Guo
mathjax: true
---

* content
{:toc}

##### Abstract
Precise segmentation is a prerequisite for an accurate quantification of the imaged objects. It is a very challenging task in many medical imaging applications due to relatively poor image quality and data scarcity. In this work, we present an innovative segmentation paradigm, named Deep Poincare Map (DPM), by coupling the dynamical system theory with a novel deep learning based approach. Firstly, we model the image segmentation process as a dynamical system, in which limit cycle models the boundary of the region of interest (ROI). Secondly, instead of segmenting the ROI directly, convolutional neural network is employed to predict the vector field of the dynamical system. Finally, the boundary of the ROI is identified using the Poincare map and the flow integration. We demonstrate that our segmentation model can be built using a very limited number of train- ing data. By cross-validation, we can achieve a mean Dice score of 94% compared to the manual delineation (ground truth) of the left ventricle ROI defined by clinical experts on a cardiac MRI dataset. Compared with other state-of-the-art methods, we can conclude that the proposed DPM method is adaptive, accurate and robust. It is straightforward to apply this method for other medical imaging applications.

##### Abstract (translated by Google)
精确分割是精确量化成像对象的先决条件。由于相对较差的图像质量和数据稀缺性，在许多医学成像应用中这是一项非常具有挑战性的任务。在这项工作中，我们提出了一个创新的分割范式，称为深Poincare映射（DPM），通过耦合动力系统理论与一种新型的深度学习为基础的方法。首先，我们将图像分割过程建模为一个动态系统，其中极限环模拟了感兴趣区域（ROI）的边界。其次，不是直接对ROI进行分割，而是采用卷积神经网络来预测动态系统的矢量场。最后，使用庞加莱图和流量整合来确定投资回报的边界。我们证明，我们的分割模型可以使用非常有限的训练数据来构建。通过交叉验证，与由心脏MRI数据集上的临床专家定义的左心室ROI的手动描绘（基本事实）相比，我们可以实现94％的平均Dice评分。与其他先进方法相比，本文提出的DPM方法具有自适应性，准确性和鲁棒性。将这种方法应用于其他医学成像应用很简单。

##### URL
[https://arxiv.org/abs/1703.09200](https://arxiv.org/abs/1703.09200)

##### PDF
[https://arxiv.org/pdf/1703.09200](https://arxiv.org/pdf/1703.09200)

