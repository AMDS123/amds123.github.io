---
layout: post
title: "On the Integration of Optical Flow and Action Recognition"
date: 2017-12-22 12:16:29
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Recognition
author: Laura Sevilla-Lara, Yiyi Liao, Fatma Guney, Varun Jampani, Andreas Geiger, Michael J. Black
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the top performing action recognition methods use optical flow as a "black box" input. Here we take a deeper look at the combination of flow and action recognition, and investigate why optical flow is helpful, what makes a flow method good for action recognition, and how we can make it better. In particular, we investigate the impact of different flow algorithms and input transformations to better understand how these affect a state-of-the-art action recognition method. Furthermore, we fine tune two neural-network flow methods end-to-end on the most widely used action recognition dataset (UCF101). Based on these experiments, we make the following five observations: 1) optical flow is useful for action recognition because it is invariant to appearance, 2) optical flow methods are optimized to minimize end-point-error (EPE), but the EPE of current methods is not well correlated with action recognition performance, 3) for the flow methods tested, accuracy at boundaries and at small displacements is most correlated with action recognition performance, 4) training optical flow to minimize classification error instead of minimizing EPE improves recognition performance, and 5) optical flow learned for the task of action recognition differs from traditional optical flow especially inside the human body and at the boundary of the body. These observations may encourage optical flow researchers to look beyond EPE as a goal and guide action recognition researchers to seek better motion cues, leading to a tighter integration of the optical flow and action recognition communities.

##### Abstract (translated by Google)
大多数顶级执行的动作识别方法使用光流作为“黑匣子”输入。在这里，我们将深入研究流动和动作识别的结合，并研究为什么光学流动是有帮助的，什么使流动方法有利于动作识别，以及如何使其更好。特别是，我们调查了不同流程算法和输入变换的影响，以便更好地理解这些如何影响最先进的动作识别方法。此外，我们在最广泛使用的动作识别数据集（UCF101）上对两种神经网络流量方法进行了端到端的微调。基于这些实验，我们做出以下五个观察：（1）光流对于动作识别是有用的，因为它的外观是不变的;（2）光流方法被优化以最小化端点误差（EPE），但EPE目前的方法与动作识别性能之间没有很好的相关性，3）对于测试的流动方法，边界和小位移的精度与动作识别性能最相关;（4）训练光流量以最小化分类错误，而不是最小化EPE; ，和5）为了识别动作而学习的光学流动与传统的光学流动不同，特别是在人体内部和身体的边界处。这些观察结果可能会鼓励光流研究人员超越EPE，将其视为一个目标，并引导行动认知研究人员寻求更好的运动线索，从而使光流和动作识别社区更紧密地结合在一起。

##### URL
[https://arxiv.org/abs/1712.08416](https://arxiv.org/abs/1712.08416)

##### PDF
[https://arxiv.org/pdf/1712.08416](https://arxiv.org/pdf/1712.08416)

