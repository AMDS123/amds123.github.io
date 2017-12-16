---
layout: post
title: "How hard is it to cross the room? -- Training Neural Networks to steer a UAV"
date: 2017-02-24 14:29:35
categories: arXiv_CV
tags: arXiv_CV Drone RNN Prediction Relation
author: Klaas Kelchtermans, Tinne Tuytelaars
mathjax: true
---

* content
{:toc}

##### Abstract
This work explores the feasibility of steering a drone with a (recurrent) neural network, based on input from a forward looking camera, in the context of a high-level navigation task. We set up a generic framework for training a network to perform navigation tasks based on imitation learning. It can be applied to both aerial and land vehicles. As a proof of concept we apply it to a UAV (Unmanned Aerial Vehicle) in a simulated environment, learning to cross a room containing a number of obstacles. So far only feedforward neural networks (FNNs) have been used to train UAV control. To cope with more complex tasks, we propose the use of recurrent neural networks (RNN) instead and successfully train an LSTM (Long-Short Term Memory) network for controlling UAVs. Vision based control is a sequential prediction problem, known for its highly correlated input data. The correlation makes training a network hard, especially an RNN. To overcome this issue, we investigate an alternative sampling method during training, namely window-wise truncated backpropagation through time (WW-TBPTT). Further, end-to-end training requires a lot of data which often is not available. Therefore, we compare the performance of retraining only the Fully Connected (FC) and LSTM control layers with networks which are trained end-to-end. Performing the relatively simple task of crossing a room already reveals important guidelines and good practices for training neural control networks. Different visualizations help to explain the behavior learned.

##### Abstract (translated by Google)
这项工作基于高级导航任务的背景下，基于来自前视摄像头的输入，探讨了使用（经常）神经网络来驾驶无人机的可行性。我们建立了一个通用的框架来训练网络来执行基于模仿学习的导航任务。它可以应用于空中和陆地车辆。作为概念证明，我们将其应用于模拟环境中的无人机（无人驾驶飞行器），学习穿越包含多个障碍物的房间。到目前为止，只有前馈神经网络（FNN）被用来训练无人机控制。为了应对更复杂的任务，我们建议使用递归神经网络（RNN），并成功训练用于控制无人机的LSTM（长短期记忆）网络。基于视觉的控制是一个顺序预测问题，以高度相关的输入数据而闻名。相关性使得训练网络变得困难，尤其是RNN。为了克服这个问题，我们研究了一种在训练期间的替代抽样方法，即通过时间的窗口截断后向传播（WW-TBPTT）。而且，端到端培训需要大量的数据，而这些数据往往不可用。因此，我们将再训练仅完全连接（FC）和LSTM控制层与端到端训练的网络的性能进行了比较。执行相对简单的穿越房间任务已经揭示了训练神经控制网络的重要指导方针和良好实践。不同的可视化有助于解释所学的行为。

##### URL
[https://arxiv.org/abs/1702.07600](https://arxiv.org/abs/1702.07600)

##### PDF
[https://arxiv.org/pdf/1702.07600](https://arxiv.org/pdf/1702.07600)

