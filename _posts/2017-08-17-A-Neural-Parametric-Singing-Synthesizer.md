---
layout: post
title: "A Neural Parametric Singing Synthesizer"
date: 2017-08-17 12:20:01
categories: arXiv_CL
tags: arXiv_CL Prediction Quantitative
author: Merlijn Blaauw, Jordi Bonada
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new model for singing synthesis based on a modified version of the WaveNet architecture. Instead of modeling raw waveform, we model features produced by a parametric vocoder that separates the influence of pitch and timbre. This allows conveniently modifying pitch to match any target melody, facilitates training on more modest dataset sizes, and significantly reduces training and generation times. Our model makes frame-wise predictions using mixture density outputs rather than categorical outputs in order to reduce the required parameter count. As we found overfitting to be an issue with the relatively small datasets used in our experiments, we propose a method to regularize the model and make the autoregressive generation process more robust to prediction errors. Using a simple multi-stream architecture, harmonic, aperiodic and voiced/unvoiced components can all be predicted in a coherent manner. We compare our method to existing parametric statistical and state-of-the-art concatenative methods using quantitative metrics and a listening test. While naive implementations of the autoregressive generation algorithm tend to be inefficient, using a smart algorithm we can greatly speed up the process and obtain a system that's competitive in both speed and quality.

##### Abstract (translated by Google)
我们提出了一个基于WaveNet架构修改版本的歌唱综合的新模型。我们不是对原始波形进行建模，而是使用参数声码器产生的特征进行建模，以分离音高和音色的影响。这允许方便地修改音调以匹配任何目标旋律，便于在更适度的数据集大小上进行训练，并且显着减少训练和生成时间。我们的模型使用混合密度输出而不是分类输出进行逐帧预测，以减少所需的参数计数。由于我们发现过拟合是我们实验中使用的相对较小的数据集的一个问题，我们提出了一种使模型正规化并使自回归生成过程对于预测误差更稳健的方法。使用简单的多流体系结构，谐波，非周期性和有声/无声分量都可以以一致的方式进行预测。我们使用定量指标和听力测试将我们的方法与现有的参数统计和最先进的连接方法进行比较。虽然自回归生成算法的天真实现往往效率低下，但使用智能算法，我们可以大大加快处理速度，并获得速度和质量都具有竞争力的系统。

##### URL
[https://arxiv.org/abs/1704.03809](https://arxiv.org/abs/1704.03809)

##### PDF
[https://arxiv.org/pdf/1704.03809](https://arxiv.org/pdf/1704.03809)

