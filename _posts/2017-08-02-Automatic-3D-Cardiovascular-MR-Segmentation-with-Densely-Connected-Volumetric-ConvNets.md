---
layout: post
title: "Automatic 3D Cardiovascular MR Segmentation with Densely-Connected Volumetric ConvNets"
date: 2017-08-02 01:47:41
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Lequan Yu, Jie-Zhi Cheng, Qi Dou, Xin Yang, Hao Chen, Jing Qin, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic and accurate whole-heart and great vessel segmentation from 3D cardiac magnetic resonance (MR) images plays an important role in the computer-assisted diagnosis and treatment of cardiovascular disease. However, this task is very challenging due to ambiguous cardiac borders and large anatomical variations among different subjects. In this paper, we propose a novel densely-connected volumetric convolutional neural network, referred as DenseVoxNet, to automatically segment the cardiac and vascular structures from 3D cardiac MR images. The DenseVoxNet adopts the 3D fully convolutional architecture for effective volume-to-volume prediction. From the learning perspective, our DenseVoxNet has three compelling advantages. First, it preserves the maximum information flow between layers by a densely-connected mechanism and hence eases the network training. Second, it avoids learning redundant feature maps by encouraging feature reuse and hence requires fewer parameters to achieve high performance, which is essential for medical applications with limited training data. Third, we add auxiliary side paths to strengthen the gradient propagation and stabilize the learning process. We demonstrate the effectiveness of DenseVoxNet by comparing it with the state-of-the-art approaches from HVSMR 2016 challenge in conjunction with MICCAI, and our network achieves the best dice coefficient. We also show that our network can achieve better performance than other 3D ConvNets but with fewer parameters.

##### Abstract (translated by Google)
自动，准确的全心和大血管分割从3D心脏磁共振（MR）图像在心血管疾病的计算机辅助诊断和治疗中起着重要的作用。然而，由于不同科目的心脏边界模糊和解剖学上的巨大差异，这项任务非常具有挑战性。在本文中，我们提出了一种新型的密集连接容积卷积神经网络，称为DenseVoxNet，可以从3D心脏MR图像自动分割心脏和血管结构。 DenseVoxNet采用3D全卷积体系结构进行有效的音量 - 音量预测。从学习的角度来看，我们的DenseVoxNet有三个引人注目的优势。首先，通过密集连接的机制保持层间最大信息流，从而简化网络训练。其次，通过鼓励特征重用来避免学习冗余特征映射，因此需要更少的参数来实现高性能，这对于训练数据有限的医学应用是必不可少的。第三，增加辅助旁路，加强梯度传播，稳定学习过程。我们将DenseVoxNet与来自HVSMR 2016挑战的最先进的方法与MICCAI相结合，展示了DenseVoxNet的有效性，并且我们的网络达到了最佳的骰子系数。我们还表明，我们的网络可以实现比其他3D通信更好的性能，但参数较少。

##### URL
[https://arxiv.org/abs/1708.00573](https://arxiv.org/abs/1708.00573)

##### PDF
[https://arxiv.org/pdf/1708.00573](https://arxiv.org/pdf/1708.00573)

