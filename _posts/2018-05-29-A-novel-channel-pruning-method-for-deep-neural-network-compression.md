---
layout: post
title: "A novel channel pruning method for deep neural network compression"
date: 2018-05-29 12:37:46
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Optimization
author: Yiming Hu, Siyang Sun, Jianquan Li, Xingang Wang, Qingyi Gu
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep neural networks have achieved great success in the field of computer vision. However, it is still a big challenge to deploy these deep models on resource-constrained embedded devices such as mobile robots, smart phones and so on. Therefore, network compression for such platforms is a reasonable solution to reduce memory consumption and computation complexity. In this paper, a novel channel pruning method based on genetic algorithm is proposed to compress very deep Convolution Neural Networks (CNNs). Firstly, a pre-trained CNN model is pruned layer by layer according to the sensitivity of each layer. After that, the pruned model is fine-tuned based on knowledge distillation framework. These two improvements significantly decrease the model redundancy with less accuracy drop. Channel selection is a combinatorial optimization problem that has exponential solution space. In order to accelerate the selection process, the proposed method formulates it as a search problem, which can be solved efficiently by genetic algorithm. Meanwhile, a two-step approximation fitness function is designed to further improve the efficiency of genetic process. The proposed method has been verified on three benchmark datasets with two popular CNN models: VGGNet and ResNet. On the CIFAR-100 and ImageNet datasets, our approach outperforms several state-of-the-art methods. On the CIFAR-10 and SVHN datasets, the pruned VGGNet achieves better performance than the original model with 8 times parameters compression and 3 times FLOPs reduction.

##### Abstract (translated by Google)
近年来，深度神经网络在计算机视觉领域取得了巨大的成功。然而，将这些深度模型部署在资源受限的嵌入式设备（如移动机器人，智能手机等）上仍然是一个巨大的挑战。因此，这种平台的网络压缩是降低内存消耗和计算复杂度的合理解决方案。本文提出了一种新的基于遗传算法的信道修剪方法对非常深的卷积神经网络（CNN）进行压缩。首先，根据每层的灵敏度对预先训练的CNN模型进行逐层修剪。之后，根据知识蒸馏框架对修剪后的模型进行微调。这两项改进显着降低了精度下降的模型冗余。信道选择是具有指数解空间的组合优化问题。为了加速选择过程，本文提出的方法将其作为一个搜索问题，可以通过遗传算法有效解决。同时，设计两步近似适应度函数来进一步提高遗传过程的效率。所提出的方法已经在两个流行的CNN模型的三个基准数据集上得到验证：VGGNet和ResNet。在CIFAR-100和ImageNet数据集上，我们的方法胜过了几种最先进的方法。在CIFAR-10和SVHN数据集上，修剪的VGGNet比原始模型具有更好的性能，其中8倍参数压缩和3倍FLOP减少。

##### URL
[http://arxiv.org/abs/1805.11394](http://arxiv.org/abs/1805.11394)

##### PDF
[http://arxiv.org/pdf/1805.11394](http://arxiv.org/pdf/1805.11394)

