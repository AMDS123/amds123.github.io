---
layout: post
title: "SE3-Pose-Nets: Structured Deep Dynamics Models for Visuomotor Planning and Control"
date: 2017-10-02 05:18:12
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Embedding Prediction
author: Arunkumar Byravan, Felix Leeb, Franziska Meier, Dieter Fox
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present an approach to deep visuomotor control using structured deep dynamics models. Our deep dynamics model, a variant of SE3-Nets, learns a low-dimensional pose embedding for visuomotor control via an encoder-decoder structure. Unlike prior work, our dynamics model is structured: given an input scene, our network explicitly learns to segment salient parts and predict their pose-embedding along with their motion modeled as a change in the pose space due to the applied actions. We train our model using a pair of point clouds separated by an action and show that given supervision only in the form of point-wise data associations between the frames our network is able to learn a meaningful segmentation of the scene along with consistent poses. We further show that our model can be used for closed-loop control directly in the learned low-dimensional pose space, where the actions are computed by minimizing error in the pose space using gradient-based methods, similar to traditional model-based control. We present results on controlling a Baxter robot from raw depth data in simulation and in the real world and compare against two baseline deep networks. Our method runs in real-time, achieves good prediction of scene dynamics and outperforms the baseline methods on multiple control runs. Video results can be found at: this https URL

##### Abstract (translated by Google)
在这项工作中，我们提出了一种深层动力学模型深度视觉控制的方法。我们的深度动力学模型（SE3-Nets的变体）通过编码器 - 解码器结构学习用于视觉控制的低维姿态嵌入。与以前的工作不同，我们的动力学模型是结构化的：给定一个输入场景，我们的网络明确地学习分割突出部分并预测它们的姿态嵌入以及由于应用动作而被建模为姿态空间的变化。我们使用由动作分开的一对点云来训练我们的模型，并且显示只有在帧之间的按点数据关联的形式下，我们的网络才能够学习有意义的场景分割以及一致的姿势。我们进一步表明，我们的模型可以直接在学习的低维姿态空间中进行闭环控制，其中通过使用基于梯度的方法使姿态空间中的误差最小化来计算动作，类似于传统的基于模型的控制。我们从仿真和现实世界中的原始深度数据展示控制Baxter机器人的结果，并与两个基线深度网络进行比较。我们的方法实时运行，可以很好地预测场景动态，并且在多个控制运行中胜过基线方法。视频结果可以在https网址找到

##### URL
[https://arxiv.org/abs/1710.00489](https://arxiv.org/abs/1710.00489)

##### PDF
[https://arxiv.org/pdf/1710.00489](https://arxiv.org/pdf/1710.00489)

