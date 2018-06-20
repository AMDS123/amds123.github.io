---
layout: post
title: "Meta Continual Learning"
date: 2018-06-11 06:49:54
categories: arXiv_AI
tags: arXiv_AI
author: Risto Vuorio, Dong-Yeon Cho, Daejoong Kim, Jiwon Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Using neural networks in practical settings would benefit from the ability of the networks to learn new tasks throughout their lifetimes without forgetting the previous tasks. This ability is limited in the current deep neural networks by a problem called catastrophic forgetting, where training on new tasks tends to severely degrade performance on previous tasks. One way to lessen the impact of the forgetting problem is to constrain parameters that are important to previous tasks to stay close to the optimal parameters. Recently, multiple competitive approaches for computing the importance of the parameters with respect to the previous tasks have been presented. In this paper, we propose a learning to optimize algorithm for mitigating catastrophic forgetting. Instead of trying to formulate a new constraint function ourselves, we propose to train another neural network to predict parameter update steps that respect the importance of parameters to the previous tasks. In the proposed meta-training scheme, the update predictor is trained to minimize loss on a combination of current and past tasks. We show experimentally that the proposed approach works in the continual learning setting.

##### Abstract (translated by Google)
在实际环境中使用神经网络可以从网络学习新任务的能力中受益，而不会忘记以前的任务。这种能力在目前的深度神经网络中受到一个称为灾难性遗忘的问题的限制，对新任务的训练往往严重降低以前任务的性能。减少遗忘问题影响的一种方法是限制对先前任务重要的参数以保持接近最优参数。最近，已经提出了多种竞争方法来计算参数相对于先前任务的重要性。在本文中，我们提出了一种学习优化算法来减轻灾难性遗忘。我们不是试图自己制定一个新的约束函数，而是提出训练另一个神经网络来预测参数更新步骤，该步骤尊重参数对以前任务的重要性。在所提出的元训练方案中，更新预测器被训练以最小化当前和过去任务的组合上的损失。我们通过实验表明，所提出的方法在连续学习环境中起作用。

##### URL
[http://arxiv.org/abs/1806.06928](http://arxiv.org/abs/1806.06928)

##### PDF
[http://arxiv.org/pdf/1806.06928](http://arxiv.org/pdf/1806.06928)

