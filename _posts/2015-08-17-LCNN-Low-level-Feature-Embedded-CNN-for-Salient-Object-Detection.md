---
layout: post
title: "LCNN: Low-level Feature Embedded CNN for Salient Object Detection"
date: 2015-08-17 05:45:12
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Hongyang Li, Huchuan Lu, Zhe Lin, Xiaohui Shen, Brian Price
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel deep neural network framework embedded with low-level features (LCNN) for salient object detection in complex images. We utilise the advantage of convolutional neural networks to automatically learn the high-level features that capture the structured information and semantic context in the image. In order to better adapt a CNN model into the saliency task, we redesign the network architecture based on the small-scale datasets. Several low-level features are extracted, which can effectively capture contrast and spatial information in the salient regions, and incorporated to compensate with the learned high-level features at the output of the last fully connected layer. The concatenated feature vector is further fed into a hinge-loss SVM detector in a joint discriminative learning manner and the final saliency score of each region within the bounding box is obtained by the linear combination of the detector's weights. Experiments on three challenging benchmark (MSRA-5000, PASCAL-S, ECCSD) demonstrate our algorithm to be effective and superior than most low-level oriented state-of-the-arts in terms of P-R curves, F-measure and mean absolute errors.

##### Abstract (translated by Google)
在本文中，我们提出了一种嵌入低级特征的深度神经网络框架（LCNN）用于复杂图像中的显着物体检测。我们利用卷积神经网络的优势来自动学习捕捉图像中结构化信息和语义上下文的高级特征。为了使CNN模型更好地适应显着性任务，我们重新设计了基于小规模数据集的网络体系结构。提取出几个低级特征，可以有效地捕获显着区域的对比度和空间信息，并结合最后完全连通层输出的学习高层特征进行补偿。级联特征向量以联合鉴别学习方式进一步馈入铰链损失支持向量机检测器，并通过检测器权值的线性组合得到边界框内每个区域的最终显着性分值。在三个具有挑战性的基准（MSRA-5000，PASCAL-S，ECCSD）上的实验证明了我们的算法在PR曲线，F-测量和平均绝对误差方面比大多数低级定向的现状有效和优越。

##### URL
[https://arxiv.org/abs/1508.03928](https://arxiv.org/abs/1508.03928)

##### PDF
[https://arxiv.org/pdf/1508.03928](https://arxiv.org/pdf/1508.03928)

