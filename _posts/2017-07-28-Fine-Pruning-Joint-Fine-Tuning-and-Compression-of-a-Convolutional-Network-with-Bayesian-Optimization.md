---
layout: post
title: "Fine-Pruning: Joint Fine-Tuning and Compression of a Convolutional Network with Bayesian Optimization"
date: 2017-07-28 04:40:32
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Recognition
author: Frederick Tung, Srikanth Muralidharan, Greg Mori
mathjax: true
---

* content
{:toc}

##### Abstract
When approaching a novel visual recognition problem in a specialized image domain, a common strategy is to start with a pre-trained deep neural network and fine-tune it to the specialized domain. If the target domain covers a smaller visual space than the source domain used for pre-training (e.g. ImageNet), the fine-tuned network is likely to be over-parameterized. However, applying network pruning as a post-processing step to reduce the memory requirements has drawbacks: fine-tuning and pruning are performed independently; pruning parameters are set once and cannot adapt over time; and the highly parameterized nature of state-of-the-art pruning methods make it prohibitive to manually search the pruning parameter space for deep networks, leading to coarse approximations. We propose a principled method for jointly fine-tuning and compressing a pre-trained convolutional network that overcomes these limitations. Experiments on two specialized image domains (remote sensing images and describable textures) demonstrate the validity of the proposed approach.

##### Abstract (translated by Google)
当在一个专门的图像领域接近一个新的视觉识别问题时，一个共同的策略是从一个预先训练的深度神经网络开始，并将其微调到专门的领域。如果目标域比用于预训练的源域（例如ImageNet）覆盖更小的视觉空间，则精细调整的网络可能被过度参数化。然而，将网络修剪作为后处理步骤来减少内存需求有一些缺点：微调和修剪是独立进行的;修剪参数设置一次，不能随时间调整;而最先进的修剪方法的高度参数化特性使得人们无法手工搜索深度网络的修剪参数空间，导致粗略的近似。我们提出了一个原则性的方法来联合微调和压缩预先训练的卷积网络，克服了这些限制。在两个专门的图像领域（遥感图像和描述纹理）的实验证明了所提出的方法的有效性。

##### URL
[https://arxiv.org/abs/1707.09102](https://arxiv.org/abs/1707.09102)

##### PDF
[https://arxiv.org/pdf/1707.09102](https://arxiv.org/pdf/1707.09102)

