---
layout: post
title: "Using Simulation to Improve Sample-Efficiency of Bayesian Optimization for Bipedal Robots"
date: 2018-05-07 20:29:50
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Akshara Rai, Rika Antonova, Franziska Meier, Christopher G. Atkeson
mathjax: true
---

* content
{:toc}

##### Abstract
Learning for control can acquire controllers for novel robotic tasks, paving the path for autonomous agents. Such controllers can be expert-designed policies, which typically require tuning of parameters for each task scenario. In this context, Bayesian optimization (BO) has emerged as a promising approach for automatically tuning controllers. However, when performing BO on hardware for high-dimensional policies, sample-efficiency can be an issue. Here, we develop an approach that utilizes simulation to map the original parameter space into a domain-informed space. During BO, similarity between controllers is now calculated in this transformed space. Experiments on the ATRIAS robot hardware and another bipedal robot simulation show that our approach succeeds at sample-efficiently learning controllers for multiple robots. Another question arises: What if the simulation significantly differs from hardware? To answer this, we create increasingly approximate simulators and study the effect of increasing simulation-hardware mismatch on the performance of Bayesian optimization. We also compare our approach to other approaches from literature, and find it to be more reliable, especially in cases of high mismatch. Our experiments show that our approach succeeds across different controller types, bipedal robot models and simulator fidelity levels, making it applicable to a wide range of bipedal locomotion problems.

##### Abstract (translated by Google)
为控制学习可以获得新型机器人任务的控制器，为自主机构铺平道路。这种控制器可以是专家设计的策略，通常需要调整每个任务场景的参数。在这种情况下，贝叶斯优化（BO）已经成为自动调节控制器的有前途的方法。但是，在高维政策的硬件上执行BO时，样本效率可能会成为问题。在这里，我们开发了一种利用仿真将原始参数空间映射到域通知空间的方法。在BO期间，现在在这个变换的空间中计算控制器之间的相似性。 ATRIAS机器人硬件和另一种双足机器人仿真的实验表明，我们的方法成功地用于高效学习多个机器人的控制器。另一个问题出现了：如果模拟与硬件显着不同，该怎么办？为了回答这个问题，我们创建了越来越近似的仿真器，并研究了增加模拟 - 硬件不匹配对贝叶斯优化性能的影响。我们还将我们的方法与文献中的其他方法进行比较，发现它更可靠，特别是在高度不匹配的情况下。我们的实验表明，我们的方法在不同的控制器类型，双足机器人模型和模拟器保真度水平上成功，使其适用于广泛的双足运动问题。

##### URL
[http://arxiv.org/abs/1805.02732](http://arxiv.org/abs/1805.02732)

##### PDF
[http://arxiv.org/pdf/1805.02732](http://arxiv.org/pdf/1805.02732)

