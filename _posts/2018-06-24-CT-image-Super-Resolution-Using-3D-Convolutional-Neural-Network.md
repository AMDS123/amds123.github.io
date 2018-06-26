---
layout: post
title: "CT-image Super Resolution Using 3D Convolutional Neural Network"
date: 2018-06-24 03:22:33
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Deep_Learning Gradient_Descent
author: Yukai Wang, Qizhi Teng, Xiaohai He, Junxi Feng, Tingrong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Computed Tomography (CT) imaging technique is widely used in geological exploration, medical diagnosis and other fields. In practice, however, the resolution of CT image is usually limited by scanning devices and great expense. Super resolution (SR) methods based on deep learning have achieved surprising performance in two-dimensional (2D) images. Unfortunately, there are few effective SR algorithms for three-dimensional (3D) images. In this paper, we proposed a novel network named as three-dimensional super resolution convolutional neural network (3DSRCNN) to realize voxel super resolution for CT images. To solve the practical problems in training process such as slow convergence of network training, insufficient memory, etc., we utilized adjustable learning rate, residual-learning, gradient clipping, momentum stochastic gradient descent (SGD) strategies to optimize training procedure. In addition, we have explored the empirical guidelines to set appropriate number of layers of network and how to use residual learning strategy. Additionally, previous learning-based algorithms need to separately train for different scale factors for reconstruction, yet our single model can complete the multi-scale SR. At last, our method has better performance in terms of PSNR, SSIM and efficiency compared with conventional methods.

##### Abstract (translated by Google)
计算机断层扫描（CT）成像技术广泛应用于地质勘探，医学诊断等领域。然而，在实践中，CT图像的分辨率通常受到扫描装置的限制并且花费很大。基于深度学习的超分辨率（SR）方法在二维（2D）图像中取得了惊人的性能。不幸的是，对于三维（3D）图像几乎没有有效的SR算法。在本文中，我们提出了一种新颖的网络，即三维超分辨率卷积神经网络（3DSRCNN）来实现CT图像的体素超分辨率。针对训练过程中网络训练收敛速度慢，记忆力不足等实际问题，采用可调学习率，残差学习，梯度裁剪，动量随机梯度下降（SGD）等策略优化训练过程。另外，我们探索了设定合适的网络层数以及如何使用残差学习策略的经验性指导方针。此外，以前的基于学习的算法需要分别训练不同的比例因子进行重建，但我们的单一模型可以完成多尺度的SR。最后，与常规方法相比，我们的方法在PSNR，SSIM和效率方面具有更好的性能。

##### URL
[http://arxiv.org/abs/1806.09074](http://arxiv.org/abs/1806.09074)

##### PDF
[http://arxiv.org/pdf/1806.09074](http://arxiv.org/pdf/1806.09074)

