---
layout: post
title: "Driving Experience Transfer Method for End-to-End Control of Self-Driving Cars"
date: 2018-09-06 05:00:10
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning
author: Dooseop Choi, Taeg-Hyun An, Kyounghwan Ahn, Jeongdan Choi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a transfer learning method for the end-to-end control of self-driving cars, which enables a convolutional neural network (CNN) trained on a source domain to be utilized for the same task in a different target domain. A conventional CNN for the end-to-end control is designed to map a single front-facing camera image to a steering command. To enable the transfer learning, we let the CNN produce not only a steering command but also a lane departure level (LDL) by adding a new task module, which takes the output of the last convolutional layer as input. The CNN trained on the source domain, called source network, is then utilized to train another task module called target network, which also takes the output of the last convolutional layer of the source network and is trained to produce a steering command for the target domain. The steering commands from the source and target network are finally merged according to the LDL and the merged command is utilized for controlling a car in the target domain. To demonstrate the effectiveness of the proposed method, we utilized two simulators, TORCS and GTAV, for the source and the target domains, respectively. Experimental results show that the proposed method outperforms other baseline methods in terms of stable and safe control of cars.

##### Abstract (translated by Google)
在本文中，我们提出了一种用于自动驾驶汽车端到端控制的转移学习方法，该方法使得在源域上训练的卷积神经网络（CNN）能够用于不同目标域中的相同任务。 。用于端到端控制的传统CNN被设计为将单个前置摄像机图像映射到转向命令。为了启用转移学习，我们通过添加新的任务模块让CNN不仅产生转向命令而且产生车道偏离等级（LDL），该任务模块将最后一个卷积层的输出作为输入。然后利用在源域上训练的CNN（称为源网络）来训练另一个称为目标网络的任务模块，该目标网络还获取源网络的最后卷积层的输出并且被训练以产生针对目标域的导向命令。 。来自源网络和目标网络的转向命令最终根据LDL合并，并且合并的命令用于控制目标域中的汽车。为了证明所提方法的有效性，我们分别为源域和目标域使用了两个模拟器TORCS和GTAV。实验结果表明，该方法在稳定安全控制汽车方面优于其他基线方法。

##### URL
[http://arxiv.org/abs/1809.01822](http://arxiv.org/abs/1809.01822)

##### PDF
[http://arxiv.org/pdf/1809.01822](http://arxiv.org/pdf/1809.01822)

