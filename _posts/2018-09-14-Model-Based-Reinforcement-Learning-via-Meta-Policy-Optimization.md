---
layout: post
title: "Model-Based Reinforcement Learning via Meta-Policy Optimization"
date: 2018-09-14 01:15:28
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Prediction
author: Ignasi Clavera, Jonas Rothfuss, John Schulman, Yasuhiro Fujita, Tamim Asfour, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Model-based reinforcement learning approaches carry the promise of being data efficient. However, due to challenges in learning dynamics models that sufficiently match the real-world dynamics, they struggle to achieve the same asymptotic performance as model-free methods. We propose Model-Based Meta-Policy-Optimization (MB-MPO), an approach that foregoes the strong reliance on accurate learned dynamics models. Using an ensemble of learned dynamic models, MB-MPO meta-learns a policy that can quickly adapt to any model in the ensemble with one policy gradient step. This steers the meta-policy towards internalizing consistent dynamics predictions among the ensemble while shifting the burden of behaving optimally w.r.t. the model discrepancies towards the adaptation step. Our experiments show that MB-MPO is more robust to model imperfections than previous model-based approaches. Finally, we demonstrate that our approach is able to match the asymptotic performance of model-free methods while requiring significantly less experience.

##### Abstract (translated by Google)
基于模型的强化学习方法具有数据有效性的前景。然而，由于学习动力学模型中的挑战与现实世界的动力学充分匹配，他们很难实现与无模型方法相同的渐近性能。我们提出了基于模型的元策略优化（MB-MPO），这种方法可以放弃对准确学习动态模型的强烈依赖。使用学习动态模型的集合，MB-MPO元学习一种策略，该策略可以通过一个策略梯度步骤快速适应集合中的任何模型。这引导了元策略，即在集合中实现一致的动态预测内部化，同时最大限度地改变行为的负担w.r.t.模型与适应步骤的差异。我们的实验表明MB-MPO比先前基于模型的方法更能够模拟缺陷。最后，我们证明了我们的方法能够匹配无模型方法的渐近性能，同时需要极少的经验。

##### URL
[http://arxiv.org/abs/1809.05214](http://arxiv.org/abs/1809.05214)

##### PDF
[http://arxiv.org/pdf/1809.05214](http://arxiv.org/pdf/1809.05214)

