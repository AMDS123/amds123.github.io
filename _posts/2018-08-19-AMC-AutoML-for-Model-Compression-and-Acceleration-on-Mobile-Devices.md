---
layout: post
title: "AMC: AutoML for Model Compression and Acceleration on Mobile Devices"
date: 2018-08-19 19:34:30
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Inference
author: Yihui He, Ji Lin, Zhijian Liu, Hanrui Wang, Li-Jia Li, Song Han
mathjax: true
---

* content
{:toc}

##### Abstract
Model compression is a critical technique to efficiently deploy neural network models on mobile devices which have limited computation resources and tight power budgets. Conventional model compression techniques rely on hand-crafted heuristics and rule-based policies that require domain experts to explore the large design space trading off among model size, speed, and accuracy, which is usually sub-optimal and time-consuming. In this paper, we propose AutoML for Model Compression (AMC) which leverage reinforcement learning to provide the model compression policy. This learning-based compression policy outperforms conventional rule-based compression policy by having higher compression ratio, better preserving the accuracy and freeing human labor. Under 4x FLOPs reduction, we achieved 2.7% better accuracy than the hand- crafted model compression policy for VGG-16 on ImageNet. We applied this automated, push-the-button compression pipeline to MobileNet and achieved 1.95x speedup of measured inference latency on an Android phone and 1.53x speedup on the Titan XP GPU, with only 0.1% loss of ImageNet Top-1 accuracy.

##### Abstract (translated by Google)
模型压缩是在具有有限计算资源和紧张功率预算的移动设备上有效部署神经网络模型的关键技术。传统的模型压缩技术依赖于手工制作的启发式和基于规则的策略，这些策略要求领域专家探索在模型大小，速度和准确性之间进行权衡的大型设计空间，这通常是次优和耗时的。在本文中，我们提出了AutoML for Model Compression（AMC），它利用强化学习来提供模型压缩策略。这种基于学习的压缩策略优于传统的基于规则的压缩策略，具有更高的压缩比，更好地保持准确性并释放人工。在4倍FLOP减少的情况下，我们比ImageNet上的VGG-16手工制作的模型压缩策略的准确率提高了2.7％。我们将这种自动化的按钮式压缩管道应用于MobileNet，并在Android手机上实现了1.95倍的测量推断延迟，在Titan XP GPU上实现了1.53倍的加速，ImageNet Top-1精度仅下降了0.1％。

##### URL
[http://arxiv.org/abs/1802.03494](http://arxiv.org/abs/1802.03494)

##### PDF
[http://arxiv.org/pdf/1802.03494](http://arxiv.org/pdf/1802.03494)

