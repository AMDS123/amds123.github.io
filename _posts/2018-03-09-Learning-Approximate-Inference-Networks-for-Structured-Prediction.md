---
layout: post
title: "Learning Approximate Inference Networks for Structured Prediction"
date: 2018-03-09 03:50:24
categories: arXiv_CL
tags: arXiv_CL Inference Classification Language_Model Prediction Gradient_Descent
author: Lifu Tu, Kevin Gimpel
mathjax: true
---

* content
{:toc}

##### Abstract
Structured prediction energy networks (SPENs; Belanger &amp; McCallum 2016) use neural network architectures to define energy functions that can capture arbitrary dependencies among parts of structured outputs. Prior work used gradient descent for inference, relaxing the structured output to a set of continuous variables and then optimizing the energy with respect to them. We replace this use of gradient descent with a neural network trained to approximate structured argmax inference. This "inference network" outputs continuous values that we treat as the output structure. We develop large-margin training criteria for joint training of the structured energy function and inference network. On multi-label classification we report speed-ups of 10-60x compared to (Belanger et al, 2017) while also improving accuracy. For sequence labeling with simple structured energies, our approach performs comparably to exact inference while being much faster at test time. We then demonstrate improved accuracy by augmenting the energy with a "label language model" that scores entire output label sequences, showing it can improve handling of long-distance dependencies in part-of-speech tagging. Finally, we show how inference networks can replace dynamic programming for test-time inference in conditional random fields, suggestive for their general use for fast inference in structured settings.

##### Abstract (translated by Google)
结构化预测能量网络（SPEN; Belanger＆amp; McCallum2016）使用神经网络体系结构来定义能量函数，其可以捕获结构化输出的部分之间的任意依赖性。先前的工作使用梯度下降进行推理，将结构化输出放宽为一组连续变量，然后针对它们优化能量。我们用经过训练的神经网络代替梯度下降的这种用法来逼近结构化的argmax推断。这个“推理网络”输出连续的值，我们将其视为输出结构。我们为结构化能源功能和推理网络的联合培训制定了大量的培训标准。在多标签分类上，与（Belanger等，2017）相比，我们报告的加速度提高了10-60倍，同时也提高了准确性。对于具有简单结构能量的序列标记，我们的方法在测试时快得多，同时精确推断更快。然后，我们通过使用“标签语言模型”来增加能量来提高精度，该标签语言模型对整个输出标签序列进行评分，表明它可以改进对词性标注中的长距离依赖性的处理。最后，我们展示推理网络如何取代动态规划，以便在条件随机域中进行测试时推断，这提示它们在结构化设置中快速推理的一般用法。

##### URL
[http://arxiv.org/abs/1803.03376](http://arxiv.org/abs/1803.03376)

##### PDF
[http://arxiv.org/pdf/1803.03376](http://arxiv.org/pdf/1803.03376)

