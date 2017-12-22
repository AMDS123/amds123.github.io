---
layout: post
title: "A Deep Policy Inference Q-Network for Multi-Agent Systems"
date: 2017-12-21 11:53:35
categories: arXiv_AI
tags: arXiv_AI Attention Reinforcement_Learning Inference
author: Zhang-Wei Hong, Shih-Yang Su, Tzu-Yun Shann, Yi-Hsiang Chang, Chun-Yi Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We present DPIQN, a deep policy inference Q-network that targets multi-agent systems composed of controllable agents, collaborators, and opponents that interact with each other. We focus on one challenging issue in such systems---modeling agents with varying strategies---and propose to employ "policy features" learned from raw observations (e.g., raw images) of collaborators and opponents by inferring their policies. DPIQN incorporates the learned policy features as a hidden vector into its own deep Q-network (DQN), such that it is able to predict better Q values for the controllable agents than the state-of-the-art deep reinforcement learning models. We further propose an enhanced version of DPIQN, called deep recurrent policy inference Q-network (DRPIQN), for handling partial observability. Both DPIQN and DRPIQN are trained by an adaptive training procedure, which adjusts the network's attention to learn the policy features and its own Q-values at different phases of the training process. We present a comprehensive analysis of DPIQN and DRPIQN, and highlight their effectiveness and generalizability in various multi-agent settings. Our models are evaluated in a classic soccer game involving both competitive and collaborative scenarios. Experimental results performed on 1 vs. 1 and 2 vs. 2 games show that DPIQN and DRPIQN demonstrate superior performance to the baseline DQN and deep recurrent Q-network (DRQN) models. We also explore scenarios in which collaborators or opponents dynamically change their policies, and show that DPIQN and DRPIQN do lead to better overall performance in terms of stability and mean scores.

##### Abstract (translated by Google)
我们提出DPIQN，这是一个深度的政策推理Q网络，其目标是由可控代理人，合作者和彼此交互的对手组成的多代理系统。我们专注于这样的系统中的一个具有挑战性的问题---建模具有不同策略的代理---并且通过推断他们的策略来提议使用从合作者和反对者的原始观察（例如原始图像）学习的“策略特征”。 DPIQN将所学习的策略特征作为隐藏向量并入其自身的深度Q网络（DQN）中，从而能够比现有技术的深度强化学习模型更好地预测可控制的代理的Q值。我们进一步提出了DPIQN的增强版本，称为深度循环策略推理Q网络（DRPIQN），用于处理局部可观测性。 DPIQN和DRPIQN均通过适应性训练程序进行训练，该训练程序调整网络的注意力以在训练过程的不同阶段学习策略特征及其自身Q值。我们提出了DPIQN和DRPIQN的综合分析，并强调了它们在各种多主体设置中的有效性和一般性。我们的模型在经典的足球比赛中进行评估，涉及竞争和协作场景。在1比1和2比2的比赛中进行的实验结果表明，DPIQN和DRPIQN表现出优于基线DQN和深回归Q网络（DRQN）模型的性能。我们还探讨了合作者或反对者动态地改变他们的政策的情景，并且表明DPIQN和DRPIQN在稳定性和平均分数方面确实导致更好的总体表现。

##### URL
[http://arxiv.org/abs/1712.07893](http://arxiv.org/abs/1712.07893)

##### PDF
[http://arxiv.org/pdf/1712.07893](http://arxiv.org/pdf/1712.07893)

