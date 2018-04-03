---
layout: post
title: "Universal Planning Networks"
date: 2018-04-02 17:51:53
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Gradient_Descent
author: Aravind Srinivas, Allan Jabri, Pieter Abbeel, Sergey Levine, Chelsea Finn
mathjax: true
---

* content
{:toc}

##### Abstract
A key challenge in complex visuomotor control is learning abstract representations that are effective for specifying goals, planning, and generalization. To this end, we introduce universal planning networks (UPN). UPNs embed differentiable planning within a goal-directed policy. This planning computation unrolls a forward model in a latent space and infers an optimal action plan through gradient descent trajectory optimization. The plan-by-gradient-descent process and its underlying representations are learned end-to-end to directly optimize a supervised imitation learning objective. We find that the representations learned are not only effective for goal-directed visual imitation via gradient-based trajectory optimization, but can also provide a metric for specifying goals using images. The learned representations can be leveraged to specify distance-based rewards to reach new target states for model-free reinforcement learning, resulting in substantially more effective learning when solving new tasks described via image-based goals. We were able to achieve successful transfer of visuomotor planning strategies across robots with significantly different morphologies and actuation capabilities.

##### Abstract (translated by Google)
复杂的视觉运动控制中的一个关键挑战是学习抽象表示，这些抽象表示对指定目标，规划和概括是有效的。为此，我们引入通用计划网络（UPN）。 UPN在目标导向政策中嵌入了可区分的规划。这个计划计算展示了潜在空间中的正向模型，并通过梯度下降轨迹优化推断出最佳行动计划。直接优化一个有监督的模仿学习目标，逐步学习逐步渐变过程及其基本表征。我们发现，通过基于梯度的轨迹优化，所学习的表示不仅对目标导向的视觉模仿有效，而且还可以提供使用图像指定目标的度量。学习表示可以用来指定基于距离的奖励，以达到无模型强化学习的新目标状态，从而在解决通过基于图像的目标描述的新任务时实现更有效的学习。我们能够成功实现跨机器人的视觉运动计划策略转移，形态和驱动能力显着不同。

##### URL
[http://arxiv.org/abs/1804.00645](http://arxiv.org/abs/1804.00645)

##### PDF
[http://arxiv.org/pdf/1804.00645](http://arxiv.org/pdf/1804.00645)

