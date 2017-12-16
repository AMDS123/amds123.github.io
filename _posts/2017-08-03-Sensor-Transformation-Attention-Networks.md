---
layout: post
title: "Sensor Transformation Attention Networks"
date: 2017-08-03 06:35:36
categories: arXiv_CV
tags: arXiv_CV Attention
author: Stefan Braun, Daniel Neil, Enea Ceolini, Jithendar Anumula, Shih-Chii Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work on encoder-decoder models for sequence-to-sequence mapping has shown that integrating both temporal and spatial attention mechanisms into neural networks increases the performance of the system substantially. In this work, we report on the application of an attentional signal not on temporal and spatial regions of the input, but instead as a method of switching among inputs themselves. We evaluate the particular role of attentional switching in the presence of dynamic noise in the sensors, and demonstrate how the attentional signal responds dynamically to changing noise levels in the environment to achieve increased performance on both audio and visual tasks in three commonly-used datasets: TIDIGITS, Wall Street Journal, and GRID. Moreover, the proposed sensor transformation network architecture naturally introduces a number of advantages that merit exploration, including ease of adding new sensors to existing architectures, attentional interpretability, and increased robustness in a variety of noisy environments not seen during training. Finally, we demonstrate that the sensor selection attention mechanism of a model trained only on the small TIDIGITS dataset can be transferred directly to a pre-existing larger network trained on the Wall Street Journal dataset, maintaining functionality of switching between sensors to yield a dramatic reduction of error in the presence of noise.

##### Abstract (translated by Google)
编码器 - 解码器模型用于序列到序列映射的最新工作表明，将时间和空间的注意力机制整合到神经网络中可显着提高系统的性能。在这项工作中，我们报告的注意力信号的应用不是对输入的时间和空间区域，而是作为输入本身之间的切换方法。我们评估了传感器中存在动态噪声时注意力转换的特殊作用，并且演示了注意信号如何动态响应环境中不断变化的噪声水平，从而在三个常用数据集中提高音频和视觉任务的性能： TIDIGITS，华尔街日报和GRID。此外，所提出的传感器转换网络架构自然引入了许多值得探索的优点，包括在现有架构中添加新传感器的容易性，注意解释性以及在训练期间未见到的各种嘈杂环境中增强的鲁棒性。最后，我们证明，仅在小TIDIGITS数据集上训练的模型的传感器选择关注机制可以被直接转移到在“华尔街日报”数据集上训练的预先存在的较大网络上，保持传感器之间切换的功能以产生显着的降低在有噪音的情况下出现错误。

##### URL
[https://arxiv.org/abs/1708.01015](https://arxiv.org/abs/1708.01015)

##### PDF
[https://arxiv.org/pdf/1708.01015](https://arxiv.org/pdf/1708.01015)

