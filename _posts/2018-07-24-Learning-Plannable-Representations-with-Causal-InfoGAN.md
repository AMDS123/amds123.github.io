---
layout: post
title: "Learning Plannable Representations with Causal InfoGAN"
date: 2018-07-24 20:46:05
categories: arXiv_AI
tags: arXiv_AI GAN Represenation_Learning
author: Thanard Kurutach, Aviv Tamar, Ge Yang, Stuart Russell, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep generative models have been shown to 'imagine' convincing high-dimensional observations such as images, audio, and even video, learning directly from raw data. In this work, we ask how to imagine goal-directed visual plans -- a plausible sequence of observations that transition a dynamical system from its current configuration to a desired goal state, which can later be used as a reference trajectory for control. We focus on systems with high-dimensional observations, such as images, and propose an approach that naturally combines representation learning and planning. Our framework learns a generative model of sequential observations, where the generative process is induced by a transition in a low-dimensional planning model, and an additional noise. By maximizing the mutual information between the generated observations and the transition in the planning model, we obtain a low-dimensional representation that best explains the causal nature of the data. We structure the planning model to be compatible with efficient planning algorithms, and we propose several such models based on either discrete or continuous states. Finally, to generate a visual plan, we project the current and goal observations onto their respective states in the planning model, plan a trajectory, and then use the generative model to transform the trajectory to a sequence of observations. We demonstrate our method on imagining plausible visual plans of rope manipulation.

##### Abstract (translated by Google)
近年来，深度生成模型已被证明可以“想象”令人信服的高维观察，如图像，音频甚至视频，直接从原始数据中学习。在这项工作中，我们询问如何设想目标导向的视觉计划 - 一个合理的观察序列，将动态系统从其当前配置转换到所需的目标状态，以后可以将其用作控制的参考轨迹。我们专注于具有高维观测的系统，例如图像，并提出一种自然地结合表示学习和规划的方法。我们的框架学习了连续观察的生成模型，其中生成过程是由低维规划模型中的过渡和额外的噪声引起的。通过最大化生成的观测值与规划模型中的过渡之间的互信息，我们获得了一个低维表示，可以最好地解释数据的因果性。我们将规划模型构建为与高效规划算法兼容，并且我们基于离散或连续状态提出了几个这样的模型。最后，为了生成视觉计划，我们将当前和目标观测投影到规划模型中的各自状态，计划轨迹，然后使用生成模型将轨迹转换为一系列观测。我们展示了我们想象绳索操纵的合理视觉计划的方法。

##### URL
[http://arxiv.org/abs/1807.09341](http://arxiv.org/abs/1807.09341)

##### PDF
[http://arxiv.org/pdf/1807.09341](http://arxiv.org/pdf/1807.09341)

