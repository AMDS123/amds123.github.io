---
layout: post
title: "Towards Mixed Optimization for Reinforcement Learning with Program Synthesis"
date: 2018-07-01 21:52:07
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Gradient_Descent
author: Surya Bhupatiraju, Kumar Krishna Agrawal, Rishabh Singh
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning has led to several recent breakthroughs, though the learned policies are often based on black-box neural networks. This makes them difficult to interpret and to impose desired specification constraints during learning. We present an iterative framework, MORL, for improving the learned policies using program synthesis. Concretely, we propose to use synthesis techniques to obtain a symbolic representation of the learned policy, which can then be debugged manually or automatically using program repair. After the repair step, we use behavior cloning to obtain the policy corresponding to the repaired program, which is then further improved using gradient descent. This process continues until the learned policy satisfies desired constraints. We instantiate MORL for the simple CartPole problem and show that the programmatic representation allows for high-level modifications that in turn lead to improved learning of the policies.

##### Abstract (translated by Google)
虽然学到的政策通常基于黑盒神经网络，但深度强化学习已经带来了最近的几项突破。这使得它们难以解释并且在学习期间施加期望的规范约束。我们提出了一个迭代框架MORL，用于使用程序综合改进学习策略。具体地说，我们建议使用合成技术来获得学习策略的符号表示，然后可以手动或使用程序修复自动调试。在修复步骤之后，我们使用行为克隆来获得与修复程序相对应的策略，然后使用梯度下降进一步改进。该过程继续，直到所学习的策略满足期望的约束。我们为简单的CartPole问题实例化MORL，并表明程序化表示允许高级修改，这反过来导致改进策略的学习。

##### URL
[http://arxiv.org/abs/1807.00403](http://arxiv.org/abs/1807.00403)

##### PDF
[http://arxiv.org/pdf/1807.00403](http://arxiv.org/pdf/1807.00403)

