---
layout: post
title: "Intelligent Trainer for Model-Based Reinforcement Learning"
date: 2018-05-24 03:08:40
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Yuanlong Li, Linsen Dong, Yonggang Wen, Kyle Guan
mathjax: true
---

* content
{:toc}

##### Abstract
Model-based deep reinforcement learning (DRL) algorithm uses the sampled data from a real environment to learn the underlying system dynamics to construct an approximate cyber environment. By using the synthesized data generated from the cyber environment to train the target controller, the training cost can be reduced significantly. In current research, issues such as the applicability of approximate model and the strategy to sample and train from the real and cyber environment have not been fully investigated. To address these issues, we propose to utilize an intelligent trainer to properly use the approximate model and control the sampling and training procedure in the model-based DRL. To do so, we package the training process of a model-based DRL as a standard RL environment, and design an RL trainer to control the training process. The trainer has three control actions: the first action controls where to sample in the real and cyber environment; the second action determines how many data should be sampled from the cyber environment and the third action controls how many times the cyber data should be used to train the target controller. These actions would be controlled manually if without the trainer. The proposed framework is evaluated on five different tasks of OpenAI gym and the test results show that the proposed trainer achieves significant better performance than a fixed parameter model-based RL baseline algorithm. In addition, we compare the performance of the intelligent trainer to a random trainer and prove that the intelligent trainer can indeed learn on the fly. The proposed training framework can be extended to more control actions with more sophisticated trainer design to further reduce the tweak cost of model-based RL algorithms.

##### Abstract (translated by Google)
基于模型的深度强化学习（DRL）算法使用来自真实环境的采样数据来学习基础系统动力学以构建近似的网络环境。通过使用从网络环境生成的合成数据来训练目标控制器，可以显着降低培训成本。在目前的研究中，诸如近似模型的适用性以及从真实和网络环境中采样和训练的策略等问题尚未得到充分研究。为了解决这些问题，我们建议利用智能训练器来正确使用近似模型并控制基于模型的DRL中的采样和训练过程。为此，我们将基于模型的DRL的培训过程作为标准的RL环境进行打包，并设计一个RL培训师来控制培训过程。培训师有三个控制动作：第一个动作控制在真实和网络环境中的样本;第二个动作决定应从网络环境中采集多少数据，第三个动作控制网络数据应该用来训练目标控制器的次数。如果没有培训师，这些动作将被手动控制。所提出的框架在OpenAI体育场的五个不同任务上进行评估，测试结果表明，所提出的训练器比基于固定参数模型的RL基线算法具有更好的性能。此外，我们将智能教练的表现与随机教练进行比较，并证明智能教练确实可以即时学习。所提出的训练框架可以扩展到更复杂的训练器设计的更多控制动作，以进一步降低基于模型的RL算法的调整成本。

##### URL
[http://arxiv.org/abs/1805.09496](http://arxiv.org/abs/1805.09496)

##### PDF
[http://arxiv.org/pdf/1805.09496](http://arxiv.org/pdf/1805.09496)

