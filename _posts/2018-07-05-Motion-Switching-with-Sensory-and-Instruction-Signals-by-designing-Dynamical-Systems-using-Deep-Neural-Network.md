---
layout: post
title: "Motion Switching with Sensory and Instruction Signals by designing Dynamical Systems using Deep Neural Network"
date: 2018-07-05 11:15:41
categories: arXiv_RO
tags: arXiv_RO CNN Relation
author: Kanata Suzuki, Hiroki Mori, Tetsuya Ogata
mathjax: true
---

* content
{:toc}

##### Abstract
To ensure that a robot is able to accomplish an extensive range of tasks, it is necessary to achieve a flexible combination of multiple behaviors. This is because the design of task motions suited to each situation would become increasingly difficult as the number of situations and the types of tasks performed by them increase. To handle the switching and combination of multiple behaviors, we propose a method to design dynamical systems based on point attractors that accept (i) "instruction signals" for instruction-driven switching. We incorporate the (ii) "instruction phase" to form a point attractor and divide the target task into multiple subtasks. By forming an instruction phase that consists of point attractors, the model embeds a subtask in the form of trajectory dynamics that can be manipulated using sensory and instruction signals. Our model comprises two deep neural networks: a convolutional autoencoder and a multiple time-scale recurrent neural network. In this study, we apply the proposed method to manipulate soft materials. To evaluate our model, we design a cloth-folding task that consists of four subtasks and three patterns of instruction signals, which indicate the direction of motion. The results depict that the robot can perform the required task by combining subtasks based on sensory and instruction signals. And, our model determined the relations among these signals using its internal dynamics.

##### Abstract (translated by Google)
为了确保机器人能够完成广泛的任务，有必要实现多种行为的灵活组合。这是因为随着情况的数量和由它们执行的任务类型的增加，适合于每种情况的任务运动的设计将变得越来越困难。为了处理多种行为的切换和组合，我们提出了一种基于点吸引器设计动态系统的方法，该点吸引器接受（i）用于指令驱动切换的“指令信号”。我们将（ii）“指令阶段”结合起来形成一个点吸引子，并将目标任务划分为多个子任务。通过形成由点吸引器组成的指令阶段，该模型以轨迹动态的形式嵌入子任务，该子任务可以使用感知和指令信号来操纵。我们的模型包括两个深度神经网络：卷积自动编码器和多时间尺度递归神经网络。在本研究中，我们应用所提出的方法来操纵软材料。为了评估我们的模型，我们设计了一个布料折叠任务，包括四个子任务和三个指令信号模式，指示运动的方向。结果表明机器人可以通过组合基于感觉和指令信号的子任务来执行所需的任务。并且，我们的模型使用其内部动力学确定了这些信号之间的关系。

##### URL
[http://arxiv.org/abs/1712.05109](http://arxiv.org/abs/1712.05109)

##### PDF
[http://arxiv.org/pdf/1712.05109](http://arxiv.org/pdf/1712.05109)

