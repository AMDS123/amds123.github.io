---
layout: post
title: "Residual Attention Network for Image Classification"
date: 2017-04-23 10:03:49
categories: arXiv_CV
tags: arXiv_CV Attention CNN Image_Classification Classification Recognition
author: Fei Wang, Mengqing Jiang, Chen Qian, Shuo Yang, Cheng Li, Honggang Zhang, Xiaogang Wang, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose "Residual Attention Network", a convolutional neural network using attention mechanism which can incorporate with state-of-art feed forward network architecture in an end-to-end training fashion. Our Residual Attention Network is built by stacking Attention Modules which generate attention-aware features. The attention-aware features from different modules change adaptively as layers going deeper. Inside each Attention Module, bottom-up top-down feedforward structure is used to unfold the feedforward and feedback attention process into a single feedforward process. Importantly, we propose attention residual learning to train very deep Residual Attention Networks which can be easily scaled up to hundreds of layers. Extensive analyses are conducted on CIFAR-10 and CIFAR-100 datasets to verify the effectiveness of every module mentioned above. Our Residual Attention Network achieves state-of-the-art object recognition performance on three benchmark datasets including CIFAR-10 (3.90% error), CIFAR-100 (20.45% error) and ImageNet (4.8% single model and single crop, top-5 error). Note that, our method achieves 0.6% top-1 accuracy improvement with 46% trunk depth and 69% forward FLOPs comparing to ResNet-200. The experiment also demonstrates that our network is robust against noisy labels.

##### Abstract (translated by Google)
在这项工作中，我们提出了“残留注意网络”，一个使用注意机制的卷积神经网络，它可以与端到端的训练方式结合先进的前馈网络架构。我们的剩余关注网络是通过堆叠注意力模块来建立的，这些模块可以产生注意力的功能。来自不同模块的注意力特征随着层次的深入而自适应地变化。在每个注意模块中，使用自下而上的自上而下的前馈结构将前馈和反馈注意过程展开为单个前馈过程。重要的是，我们提出注意残留学习来训练非常深的残留注意力网络，这个网络可以很容易地扩展到数百层。对CIFAR-10和CIFAR-100数据集进行了大量分析，以验证上述每个模块的有效性。我们的残留注意网络在CIFAR-10（3.90％误差），CIFAR-100（20.45％误差）和ImageNet（4.8％单一模型和单一作物，顶级成像）三个基准数据集上实现了最先进的目标识别性能。 5错误）。需要注意的是，与ResNet-200相比，我们的方法可以获得0.6％的前1精度提升，46％的主干深度和69％的前向FLOP。实验还表明，我们的网络对抗嘈杂的标签是健壮的。

##### URL
[https://arxiv.org/abs/1704.06904](https://arxiv.org/abs/1704.06904)

##### PDF
[https://arxiv.org/pdf/1704.06904](https://arxiv.org/pdf/1704.06904)

