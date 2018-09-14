---
layout: post
title: "Sequential Coordination of Deep Models for Learning Visual Arithmetic"
date: 2018-09-13 14:27:25
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Eric Crawford, Guillaume Rabusseau, Joelle Pineau
mathjax: true
---

* content
{:toc}

##### Abstract
Achieving machine intelligence requires a smooth integration of perception and reasoning, yet models developed to date tend to specialize in one or the other; sophisticated manipulation of symbols acquired from rich perceptual spaces has so far proved elusive. Consider a visual arithmetic task, where the goal is to carry out simple arithmetical algorithms on digits presented under natural conditions (e.g. hand-written, placed randomly). We propose a two-tiered architecture for tackling this problem. The lower tier consists of a heterogeneous collection of information processing modules, which can include pre-trained deep neural networks for locating and extracting characters from the image, as well as modules performing symbolic transformations on the representations extracted by perception. The higher tier consists of a controller, trained using reinforcement learning, which coordinates the modules in order to solve the high-level task. For instance, the controller may learn in what contexts to execute the perceptual networks and what symbolic transformations to apply to their outputs. The resulting model is able to solve a variety of tasks in the visual arithmetic domain, and has several advantages over standard, architecturally homogeneous feedforward networks including improved sample efficiency.

##### Abstract (translated by Google)
实现机器智能需要感知和推理的平滑整合，但迄今为止开发的模型往往专注于一个或另一个;到目前为止，从丰富的感知空间获得的符号的复杂操纵已被证明是难以捉摸的。考虑一个视觉算术任务，其目标是对在自然条件下呈现的数字（例如，手写，随机放置）执行简单的算术算法。我们提出了一个解决这个问题的双层架构。较低层由信息处理模块的异构集合组成，其可包括用于从图像中定位和提取字符的预训练深度神经网络，以及对通过感知提取的表示执行符号变换的模块。较高层由控制器组成，使用强化学习训练，协调模块以解决高级任务。例如，控制器可以学习在什么上下文中执行感知网络以及应用于其输出的符号变换。得到的模型能够解决视觉算术领域中的各种任务，并且与标准的，架构上均匀的前馈网络相比具有若干优点，包括提高的样本效率。

##### URL
[http://arxiv.org/abs/1809.04988](http://arxiv.org/abs/1809.04988)

##### PDF
[http://arxiv.org/pdf/1809.04988](http://arxiv.org/pdf/1809.04988)

