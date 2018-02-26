---
layout: post
title: "Training wide residual networks for deployment using a single bit for each weight"
date: 2018-02-23 13:54:23
categories: arXiv_CV
tags: arXiv_CV CNN
author: Mark D. McDonnell
mathjax: true
---

* content
{:toc}

##### Abstract
For fast and energy-efficient deployment of trained deep neural networks on resource-constrained embedded hardware, each learned weight parameter should ideally be represented and stored using a single bit. Error-rates usually increase when this requirement is imposed. Here, we report large improvements in error rates on multiple datasets, for deep convolutional neural networks deployed with 1-bit-per-weight. Using wide residual networks as our main baseline, our approach simplifies existing methods that binarize weights by applying the sign function in training; we apply scaling factors for each layer with constant unlearned values equal to the layer-specific standard deviations used for initialization. For CIFAR-10, CIFAR-100 and ImageNet, and models with 1-bit-per-weight requiring less than 10 MB of parameter memory, we achieve error rates of 3.9%, 18.5% and 26.0% / 8.5% (Top-1 / Top-5) respectively. We also considered MNIST, SVHN and ImageNet32, achieving 1-bit-per-weight test results of 0.27%, 1.9%, and 41.3% / 19.1% respectively. For CIFAR, our error rates halve previously reported values, and are within about 1% of our error-rates for the same network with full-precision weights. For networks that overfit, we also show significant improvements in error rate by not learning batch normalization scale and offset parameters. This applies to both full precision and 1-bit-per-weight networks. Using a warm-restart learning-rate schedule, we found that training for 1-bit-per-weight is just as fast as full-precision networks, with better accuracy than standard schedules, and achieved about 98%-99% of peak performance in just 62 training epochs for CIFAR-10/100. For full training code and trained models in MATLAB, Keras and PyTorch see https://github.com/McDonnell-Lab/1-bit-per-weight/ .

##### Abstract (translated by Google)
为了在资源受限的嵌入式硬件上快速且节能地部署经训练的深度神经网络，理想地应当使用单个位来表示和存储每个学习的权重参数。在强制执行此要求时，错误率通常会增加。在这里，我们报告了在多个数据集上的错误率的显着改进，用于以1比特每重量部署的深度卷积神经网络。使用广泛的残余网络作为我们的主要基线，我们的方法简化了通过在训练中应用符号函数来二值化权重的现有方法;我们对每个图层应用比例因子，其中不变的未知数值等于用于初始化的层特定标准偏差。对于CIFAR-10，CIFAR-100和ImageNet以及重量为1比特需要少于10 MB参数存储器的型号，我们实现了3.9％，18.5％和26.0％/ 8.5％的错误率（Top-1 / Top-5）。我们还考虑了MNIST，SVHN和ImageNet32，分别实现了0.27％，1.9％和41.3％/ 19.1％的1位重量测试结果。对于CIFAR，我们的误差率先前报告的值减半，并且在具有全精度权重的相同网络中，误差率在我们的误差率的约1％内。对于过度配置的网络，我们还通过不学习批量归一化比例和偏移参数来显示错误率的显着提高。这适用于全精度和1比特每重量网络。使用热重启学习速率计划，我们发现每比特1位的训练速度与全精度网络一样快，比标准时间表具有更好的准确性，并且达到了峰值性能的约98％-99％在CIFAR-10/100只有62个训练时期。对于完整的训练代码和MATLAB中的训练模型，Keras和PyTorch请参阅https://github.com/McDonnell-Lab/1-bit-per-weight/。

##### URL
[http://arxiv.org/abs/1802.08530](http://arxiv.org/abs/1802.08530)

##### PDF
[http://arxiv.org/pdf/1802.08530](http://arxiv.org/pdf/1802.08530)

