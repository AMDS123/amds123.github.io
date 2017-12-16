---
layout: post
title: "BlockDrop: Dynamic Inference Paths in Residual Networks"
date: 2017-11-22 17:01:59
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning CNN Inference Prediction Quantitative Recognition
author: Zuxuan Wu, Tushar Nagarajan, Abhishek Kumar, Steven Rennie, Larry S. Davis, Kristen Grauman, Rogerio Feris
mathjax: true
---

* content
{:toc}

##### Abstract
Very deep convolutional neural networks offer excellent recognition results, yet their computational expense limits their impact for many real-world applications. We introduce BlockDrop, an approach that learns to dynamically choose which layers of a deep network to execute during inference so as to best reduce total computation without degrading prediction accuracy. Exploiting the robustness of Residual Networks (ResNets) to layer dropping, our framework selects on-the-fly which residual blocks to evaluate for a given novel image. In particular, given a pretrained ResNet, we train a policy network in an associative reinforcement learning setting for the dual reward of utilizing a minimal number of blocks while preserving recognition accuracy. We conduct extensive experiments on CIFAR and ImageNet. The results provide strong quantitative and qualitative evidence that these learned policies not only accelerate inference but also encode meaningful visual information. Built upon a ResNet-101 model, our method achieves a speedup of 20\% on average, going as high as 36\% for some images, while maintaining the same 76.4\% top-1 accuracy on ImageNet.

##### Abstract (translated by Google)
非常深的卷积神经网络提供了极好的识别结果，但是它们的计算费用限制了它们对许多实际应用的影响。我们引入BlockDrop，这是一种学习动态选择在推断过程中执行深层网络的哪一层的方法，以便在不降低预测精度的情况下最大限度地减少总计算量。利用剩余网络（ResNets）的鲁棒性进行分层丢弃，我们的框架即时选择要评估给定新图像的剩余块。特别是，在ResNet预训练的情况下，我们在一个关联强化学习环境中训练一个策略网络，以便在保证识别准确性的同时利用最小数量的块来获得双重奖励。我们在CIFAR和ImageNet上进行了大量的实验。这些结果提供了强有力的定量和定性证据，证明这些学习政策不仅加速推理，而且编码有意义的视觉信息。在ResNet-101模型的基础上，我们的方法平均可以实现20％的加速，对于一些图像来说高达36％，同时在ImageNet上保持了76.4％的最高精度。

##### URL
[https://arxiv.org/abs/1711.08393](https://arxiv.org/abs/1711.08393)

##### PDF
[https://arxiv.org/pdf/1711.08393](https://arxiv.org/pdf/1711.08393)

