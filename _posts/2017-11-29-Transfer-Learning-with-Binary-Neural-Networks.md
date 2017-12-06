---
layout: post
title: 'Transfer Learning with Binary Neural Networks'
date: 2017-11-29 10:28:02
categories: arXiv_CV
tags: arXiv_CV
author: Sam Leroux, Steven Bohez, Tim Verbelen, Bert Vankeirsbilck, Pieter Simoens, Bart Dhoedt
---

* content
{:toc}

##### Abstract
Previous work has shown that it is possible to train deep neural networks with low precision weights and activations. In the extreme case it is even possible to constrain the network to binary values. The costly floating point multiplications are then reduced to fast logical operations. High end smart phones such as Google's Pixel 2 and Apple's iPhone X are already equipped with specialised hardware for image processing and it is very likely that other future consumer hardware will also have dedicated accelerators for deep neural networks. Binary neural networks are attractive in this case because the logical operations are very fast and efficient when implemented in hardware. We propose a transfer learning based architecture where we first train a binary network on Imagenet and then retrain part of the network for different tasks while keeping most of the network fixed. The fixed binary part could be implemented in a hardware accelerator while the last layers of the network are evaluated in software. We show that a single binary neural network trained on the Imagenet dataset can indeed be used as a feature extractor for other datasets.

##### Abstract (translated by Google)
以前的工作表明，可以训练具有低精度权重和激活的深度神经网络。在极端的情况下，甚至可以将网络限制为二进制值。昂贵的浮点乘法然后被减少到快速的逻辑操作。谷歌的像素2和苹果的iPhone X等高端智能手机已经配备了专门用于图像处理的硬件，未来的其他消费类硬件很可能也会为深度神经网络提供专用加速器。二进制神经网络在这种情况下是有吸引力的，因为在硬件中实现逻辑运算是非常快速和高效的。我们提出了一个基于转移学习的架构，我们首先在Imagenet上训练一个二进制网络，然后在不同的任务中重新训练网络的一部分，同时保持大部分网络的固定。固定的二进制部分可以在硬件加速器中实现，而网络的最后一层在软件中评估。我们表明，在Imagenet数据集上训练的单个二进制神经网络确实可以用作其他数据集的特征提取器。

##### URL
[https://arxiv.org/abs/1711.10761](https://arxiv.org/abs/1711.10761)

