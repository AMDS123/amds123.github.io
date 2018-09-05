---
layout: post
title: "Learning Low Precision Deep Neural Networks through Regularization"
date: 2018-09-01 01:28:21
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Inference
author: Yoojin Choi, Mostafa El-Khamy, Jungwon Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the quantization of deep neural networks (DNNs) to produce low-precision models for efficient inference of fixed-point operations. Compared to previous approaches to training quantized DNNs directly under the constraints of low-precision weights and activations, we learn the quantization of DNNs with minimal quantization loss through regularization. In particular, we introduce the learnable regularization coefficient to find accurate low-precision models efficiently in training. In our experiments, the proposed scheme yields the state-of-the-art low-precision models of AlexNet and ResNet-18, which have better accuracy than their previously available low-precision models. We also examine our quantization method to produce low-precision DNNs for image super resolution. We observe only $0.5$~dB peak signal-to-noise ratio (PSNR) loss when using binary weights and 8-bit activations. The proposed scheme can be used to train low-precision models from scratch or to fine-tune a well-trained high-precision model to converge to a low-precision model. Finally, we discuss how a similar regularization method can be adopted in DNN weight pruning and compression, and show that $401\times$ compression is achieved for LeNet-5.

##### Abstract (translated by Google)
我们考虑深度神经网络（DNN）的量化，以产生低精度模型，以有效推断定点运算。与先前在低精度权重和激活的约束下直接训练量化DNN的方法相比，我们通过正则化学习了具有最小量化损失的DNN的量化。特别是，我们引入了可学习的正则化系数，以便在训练中有效地找到准确的低精度模型。在我们的实验中，所提出的方案产生了AlexNet和ResNet-18的最先进的低精度模型，其具有比其先前可用的低精度模型更好的精度。我们还研究了我们的量化方法，以产生用于图像超分辨率的低精度DNN。当使用二进制加权和8位激活时，我们观察到仅0.5美元〜dB的峰值信噪比（PSNR）损失。所提出的方案可用于从头开始训练低精度模型或微调经过良好训练的高精度模型以收敛到低精度模型。最后，我们讨论了如何在DNN权重修剪和压缩中采用类似的正则化方法，并表明LeNet-5实现了$ 401 \倍$压缩。

##### URL
[http://arxiv.org/abs/1809.00095](http://arxiv.org/abs/1809.00095)

##### PDF
[http://arxiv.org/pdf/1809.00095](http://arxiv.org/pdf/1809.00095)

