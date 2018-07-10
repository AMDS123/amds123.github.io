---
layout: post
title: "An Intriguing Failing of Convolutional Neural Networks and the CoordConv Solution"
date: 2018-07-09 15:48:08
categories: arXiv_CV
tags: arXiv_CV GAN CNN Deep_Learning Detection
author: Rosanne Liu, Joel Lehman, Piero Molino, Felipe Petroski Such, Eric Frank, Alex Sergeev, Jason Yosinski
mathjax: true
---

* content
{:toc}

##### Abstract
Few ideas have enjoyed as large an impact on deep learning as convolution. For any problem involving pixels or spatial representations, common intuition holds that convolutional neural networks may be appropriate. In this paper we show a striking counterexample to this intuition via the seemingly trivial coordinate transform problem, which simply requires learning a mapping between coordinates in (x,y) Cartesian space and one-hot pixel space. Although convolutional networks would seem appropriate for this task, we show that they fail spectacularly. We demonstrate and carefully analyze the failure first on a toy problem, at which point a simple fix becomes obvious. We call this solution CoordConv, which works by giving convolution access to its own input coordinates through the use of extra coordinate channels. Without sacrificing the computational and parametric efficiency of ordinary convolution, CoordConv allows networks to learn either perfect translation invariance or varying degrees of translation dependence, as required by the task. CoordConv solves the coordinate transform problem with perfect generalization and 150 times faster with 10--100 times fewer parameters than convolution. This stark contrast raises the question: to what extent has this inability of convolution persisted insidiously inside other tasks, subtly hampering performance from within? A complete answer to this question will require further investigation, but we show preliminary evidence that swapping convolution for CoordConv can improve models on a diverse set of tasks. Using CoordConv in a GAN produced less mode collapse as the transform between high-level spatial latents and pixels becomes easier to learn. A Faster R-CNN detection model trained on MNIST detection showed 24% better IOU when using CoordConv, and in the RL domain agents playing Atari games benefit significantly from the use of CoordConv layers.

##### Abstract (translated by Google)
很少有想法像卷积一样对深度学习产生巨大影响。对于涉及像素或空间表示的任何问题，常见的直觉认为卷积神经网络可能是合适的。在本文中，我们通过看似平凡的坐标变换问题展示了这种直觉的一个引人注目的反例，它只需要学习（x，y）笛卡尔空间和单热像素空间中坐标之间的映射。虽然卷积网络似乎适合这项任务，但我们表明它们失败了。我们首先在玩具问题上展示并仔细分析故障，此时简单的修复变得明显。我们将此解决方案称为CoordConv，它通过使用额外的坐标通道对其自己的输入坐标进行卷积访问来工作。在不牺牲普通卷积的计算和参数效率的情况下，CoordConv允许网络根据任务的要求学习完美的平移不变性或不同程度的平移依赖性。 CoordConv解决了坐标变换问题，具有完美的泛化速度，速度提高了150倍，参数比卷积少10-100倍。这种鲜明的对比提出了一个问题：卷积无法在多大程度上潜伏在其他任务中，从根本上阻碍了内部的表现？这个问题的完整答案需要进一步调查，但我们展示了初步证据，即交换CoordConv的卷积可以改善各种任务的模型。在GAN中使用CoordConv产生较少的模式崩溃，因为高级空间潜伏和像素之间的转换变得更容易学习。在使用CoordConv时，使用MNIST检测训练的更快的R-CNN检测模型显示24％更好的IOU，并且在RL域中，玩Atari游戏的代理从使用CoordConv层中获益显着。

##### URL
[http://arxiv.org/abs/1807.03247](http://arxiv.org/abs/1807.03247)

##### PDF
[http://arxiv.org/pdf/1807.03247](http://arxiv.org/pdf/1807.03247)

