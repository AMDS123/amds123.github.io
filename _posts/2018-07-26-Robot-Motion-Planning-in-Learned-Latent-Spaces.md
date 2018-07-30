---
layout: post
title: "Robot Motion Planning in Learned Latent Spaces"
date: 2018-07-26 21:11:26
categories: arXiv_RO
tags: arXiv_RO Embedding
author: Brian Ichter, Marco Pavone
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents Latent Sampling-based Motion Planning (L-SBMP), a methodology towards computing motion plans for complex robotic systems by learning a plannable latent representation. Recent works in control of robotic systems have effectively leveraged local, low-dimensional embeddings of high-dimensional dynamics. In this paper we combine these recent advances with techniques from sampling-based motion planning (SBMP) in order to design a motion planning framework for high-dimensional robotic systems (e.g., humanoids, or even systems where planning occurs in the visual space). Specifically, the learned latent space is constructed through an autoencoding network, a dynamics network, and a collision checking network, which mirror the three main algorithmic primitives of SBMP, namely state sampling, local steering, and collision checking. Notably, these networks can be trained through only raw data of the system's states and actions along with a supervising collision checker. Building upon these networks, an RRT-based algorithm is used to plan motions directly in the latent space -- we refer to this exploration algorithm as Learned Latent RRT (L2RRT). This algorithm globally explores the latent space and is capable of generalizing to new environments. The overall methodology is demonstrated on two planning problems that are well beyond the reach of standard SBMP, namely a visual planning problem, whereby planning happens in the visual (pixel) space, and a humanoid robot planning problem.

##### Abstract (translated by Google)
本文介绍了基于潜在采样的运动规划（L-SBMP），这是一种通过学习可计划的潜在表示来计算复杂机器人系统运动计划的方法。最近控制机器人系统的工作有效地利用了高维动力学的局部低维嵌入。在本文中，我们将这些最新进展与基于采样的运动规划（SBMP）的技术相结合，以便为高维机器人系统（例如，类人生物，甚至是在视觉空间中进行规划的系统）设计运动规划框架。具体地，学习的潜在空间通过自动编码网络，动态网络和冲突检查网络构建，其反映了SBMP的三个主要算法原语，即状态采样，本地导向和冲突检查。值得注意的是，这些网络只能通过系统状态和动作的原始数据以及监督冲突检查器进行训练。基于这些网络，基于RRT的算法用于直接在潜在空间中规划运动 - 我们将此探索算法称为学习潜伏RRT（L2RRT）。该算法全局探索潜在空间，并能够推广到新环境。整体方法论证明了两个远远超出标准SBMP范围的规划问题，即视觉规划问题，其中规划发生在视觉（像素）空间，以及人形机器人规划问题。

##### URL
[https://arxiv.org/abs/1807.10366](https://arxiv.org/abs/1807.10366)

##### PDF
[https://arxiv.org/pdf/1807.10366](https://arxiv.org/pdf/1807.10366)

