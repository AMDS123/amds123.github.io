---
layout: post
title: "Fast Retinomorphic Event Stream for Video Recognition and ReinforcementLearning"
date: 2018-05-16 15:42:37
categories: arXiv_CV
tags: arXiv_CV Video_Caption Reinforcement_Learning Action_Recognition Inference Detection Recognition
author: Wanjia Liu, Huaijin Chen, Rishab Goel, Yuzhong Huang, Ashok Veeraraghavan, Ankit Patel
mathjax: true
---

* content
{:toc}

##### Abstract
Good temporal representations are crucial for video understanding, and the state-of-the-art video recognition frame- work is based on two-stream networks. In such framework, besides the regular ConvNets responsible for RGB frame inputs, a second network is introduced to handle the temporal representation, usually the optical flow (OF). However, OF or other task-oriented flow is computationally costly, and is thus typically pre-computed. Critically, this prevents the two-stream approach from being applied to reinforcement learning (RL) applications such as video game playing, where the next state depends on current state and action choices. Inspired by the early vision systems of mammals and in- sects, we propose a fast event-driven input representation (EDR) that models several major properties of early retinal circuits1: (1) logarithmic input response, (2) multi-timescale temporal smoothing to filter noise, and (3) bipolar (ON/OFF) pathways for primitive event detection. Trading off the directional information for fast speed (&gt; 9000 fps), EDR enables fast real-time inference/learning in video applications that require interaction between an agent and the world such as game-playing, virtual robotics, and domain adaptation. In this vein, we use EDR to demonstrate performance improvements over state-of-the-art reinforcement learning algorithms for Atari games, something that has not been possible with pre-computed OF. Moreover, with UCF-101 video action recognition experiments, we show that EDR performs near state-of-the-art in accuracy while achieving a 1,500x speedup in input representation processing ( 9K frames/sec), as compared to optical flow.

##### Abstract (translated by Google)
良好的时间表示对于视频理解至关重要，并且最先进的视频识别框架基于双流网络。在这种框架中，除了负责RGB帧输入的常规ConvNets之外，还引入了第二个网络来处理时间表示，通常是光流（OF）。然而，OF或其他面向任务的流程在计算上是昂贵的，因此通常是预先计算的。至关重要的是，这样可以防止双流方法应用于强化学习（RL）应用，例如视频游戏，其中下一个状态取决于当前状态和动作选择。受到哺乳动物和昆虫早期视觉系统的启发，我们提出了一种快速事件驱动的输入表示（EDR），它模拟早期视网膜回路的几个主要特性1：（1）对数输入响应，（2）多时间尺度时间平滑以过滤噪声，以及（3）原始事件检测的双极（ON / OFF）通路。为了实现快速（> 9000 fps）的定向信息交易，EDR能够在需要代理与世界互动的视频应用中实现快速实时推理/学习，如游戏玩法，虚拟机器人技术和领域适应。在这方面，我们使用EDR来展示性能改进，比Atari游戏的最先进的强化学习算法有所改进，这在预先计算的OF中是不可能的。此外，通过UCF-101视频动作识别实验，我们发现EDR与光流相比，在输入表示处理（9K帧/秒）中实现了1,500倍的加速，并且精度接近最新水平。

##### URL
[http://arxiv.org/abs/1805.06374](http://arxiv.org/abs/1805.06374)

##### PDF
[http://arxiv.org/pdf/1805.06374](http://arxiv.org/pdf/1805.06374)

