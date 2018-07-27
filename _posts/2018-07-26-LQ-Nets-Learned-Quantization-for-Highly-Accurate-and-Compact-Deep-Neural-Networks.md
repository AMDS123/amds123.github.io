---
layout: post
title: "LQ-Nets: Learned Quantization for Highly Accurate and Compact Deep Neural Networks"
date: 2018-07-26 09:26:39
categories: arXiv_AI
tags: arXiv_AI Inference Prediction
author: Dongqing Zhang, Jiaolong Yang, Dongqiangzi Ye, Gang Hua
mathjax: true
---

* content
{:toc}

##### Abstract
Although weight and activation quantization is an effective approach for Deep Neural Network (DNN) compression and has a lot of potentials to increase inference speed leveraging bit-operations, there is still a noticeable gap in terms of prediction accuracy between the quantized model and the full-precision model. To address this gap, we propose to jointly train a quantized, bit-operation-compatible DNN and its associated quantizers, as opposed to using fixed, handcrafted quantization schemes such as uniform or logarithmic quantization. Our method for learning the quantizers applies to both network weights and activations with arbitrary-bit precision, and our quantizers are easy to train. The comprehensive experiments on CIFAR-10 and ImageNet datasets show that our method works consistently well for various network structures such as AlexNet, VGG-Net, GoogLeNet, ResNet, and DenseNet, surpassing previous quantization methods in terms of accuracy by an appreciable margin. Code available at https://github.com/Microsoft/LQ-Nets

##### Abstract (translated by Google)
虽然权重和激活量化是深度神经网络（DNN）压缩的有效方法，并且具有提高利用位操作的推理速度的许多潜力，但在量化模型和完整模型之间的预测准确度方面仍存在明显差距。 - 精确模型。为了解决这个差距，我们建议联合训练量化的，位操作兼容的DNN及其相关的量化器，而不是使用固定的手工量化方案，例如均匀或对数量化。我们学习量化器的方法适用于任意位精度的网络权重和激活，我们的量化器很容易训练。对CIFAR-10和ImageNet数据集的全面实验表明，我们的方法可以很好地适用于各种网络结构，如AlexNet，VGG-Net，GoogLeNet，ResNet和DenseNet，在准确度方面超过以前的量化方法。代码可从https://github.com/Microsoft/LQ-Nets获得

##### URL
[http://arxiv.org/abs/1807.10029](http://arxiv.org/abs/1807.10029)

##### PDF
[http://arxiv.org/pdf/1807.10029](http://arxiv.org/pdf/1807.10029)

