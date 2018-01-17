---
layout: post
title: "GitGraph - Architecture Search Space Creation through Frequent Computational Subgraph Mining"
date: 2018-01-16 08:54:20
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Kamil Bennani-Smires, Claudiu Musat, Andreea Hossmann, Michael Baeriswyl
mathjax: true
---

* content
{:toc}

##### Abstract
The dramatic success of deep neural networks across multiple application areas often relies on experts painstakingly designing a network architecture specific to each task. To simplify this process and make it more accessible, an emerging research effort seeks to automate the design of neural network architectures, using e.g. evolutionary algorithms or reinforcement learning or simple search in a constrained space of neural modules. 
 Considering the typical size of the search space (e.g. $10^{10}$ candidates for a $10$-layer network) and the cost of evaluating a single candidate, current architecture search methods are very restricted. They either rely on static pre-built modules to be recombined for the task at hand, or they define a static hand-crafted framework within which they can generate new architectures from the simplest possible operations. 
 In this paper, we relax these restrictions, by capitalizing on the collective wisdom contained in the plethora of neural networks published in online code repositories. Concretely, we (a) extract and publish GitGraph, a corpus of neural architectures and their descriptions; (b) we create problem-specific neural architecture search spaces, implemented as a textual search mechanism over GitGraph; (c) we propose a method of identifying unique common subgraphs within the architectures solving each problem (e.g., image processing, reinforcement learning), that can then serve as modules in the newly created problem specific neural search space.

##### Abstract (translated by Google)
深度神经网络在多个应用领域的巨大成功往往依赖于专家精心设计专门针对每个任务的网络体系结构。为了简化这个过程并使其更容易获得，一个新兴的研究努力寻求使神经网络结构的设计自动化。进化算法或强化学习或在神经模块的受限空间中进行简单搜索。
 考虑到搜索空间的典型大小（例如$ 10 $  - 层网络的$ 10 ^ {10} $个候选者）和评估单个候选者的成本，当前的架构搜索方法是非常受限制的。他们要么依靠静态的预构建模块来重组手边的任务，要么定义一个静态的手工框架，在这个框架内，他们可以从最简单的操作中生成新的架构。
 在本文中，我们通过利用在线代码库中发布的大量神经网络中包含的集体智慧来放松这些限制。具体而言，我们（a）提取并发布GitGraph，一个神经架构的语料库及其描述; （b）我们创建问题特定的神经架构搜索空间，作为GitGraph上的文本搜索机制实现; （c）我们提出了一种在解决每个问题（例如，图像处理，强化学习）的体系结构中识别独特的公共子图的方法，其然后可以在新创建的特定于问题的神经搜索空间中作为模块。

##### URL
[http://arxiv.org/abs/1801.05159](http://arxiv.org/abs/1801.05159)

##### PDF
[http://arxiv.org/pdf/1801.05159](http://arxiv.org/pdf/1801.05159)

