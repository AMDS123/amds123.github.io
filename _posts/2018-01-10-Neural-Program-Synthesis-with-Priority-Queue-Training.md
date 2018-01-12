---
layout: post
title: "Neural Program Synthesis with Priority Queue Training"
date: 2018-01-10 19:35:25
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization RNN
author: Daniel A. Abolafia, Mohammad Norouzi, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the task of program synthesis in the presence of a reward function over the output of programs, where the goal is to find programs with maximal rewards. We employ an iterative optimization scheme, where we train an RNN on a dataset of K best programs from a priority queue of the generated programs so far. Then, we synthesize new programs and add them to the priority queue by sampling from the RNN. We benchmark our algorithm, called priority queue training (or PQT), against genetic algorithm and reinforcement learning baselines on a simple but expressive Turing complete programming language called BF. Our experimental results show that our simple PQT algorithm significantly outperforms the baselines. By adding a program length penalty to the reward function, we are able to synthesize short, human readable programs.

##### Abstract (translated by Google)
我们认为程序综合的任务是在程序的输出中存在一个奖励函数，目标是找到最大奖励的程序。我们采用一种迭代优化方案，在这种方案中，我们从目前生成的程序的优先级队列中对K个最佳程序的数据集进行RNN训练。然后，我们综合新的程序并通过从RNN采样将它们添加到优先级队列中。我们将我们的算法（称为优先级队列训练（PQT））与遗传算法和强化学习基线结合起来，用简单而富有表现力的Turing完整编程语言（称为BF）进行测试。我们的实验结果表明，我们简单的PQT算法明显优于基线。通过增加奖励功能的程序长度惩罚，我们能够合成短的，人类可读的程序。

##### URL
[http://arxiv.org/abs/1801.03526](http://arxiv.org/abs/1801.03526)

##### PDF
[http://arxiv.org/pdf/1801.03526](http://arxiv.org/pdf/1801.03526)

