---
layout: post
title: "Meta-Learning by Adjusting Priors Based on Extended PAC-Bayes Theory"
date: 2018-02-13 05:26:27
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Ron Amit, Ron Meir
mathjax: true
---

* content
{:toc}

##### Abstract
In meta-learning an agent extracts knowledge from observed tasks, aiming to facilitate learning of novel future tasks. Under the assumption that future tasks are 'related' to previous tasks, representations should be learned in a way which captures the common structure across learned tasks, while allowing the learner sufficient flexibility to adapt to novel aspects of new tasks. We present a framework for meta-learning that is based on generalization error bounds, allowing us to extend various PAC-Bayes bounds to meta-learning. Learning takes place through the construction of a distribution over hypotheses based on the observed tasks, and its utilization for learning a new task. Thus, prior knowledge is incorporated through setting an experience-dependent prior for novel tasks. We develop a gradient-based algorithm which minimizes an objective function derived from the bounds and demonstrate its effectiveness numerically with deep neural networks. In addition to establishing the improved performance available through meta-learning, we demonstrate the intuitive way by which prior information is manifested at different levels of the network.

##### Abstract (translated by Google)
在元学习中，代理从观察到的任务中提取知识，旨在促进学习未来新任务。在假设未来的任务与以前的任务“相关”的前提下，应该以一种能够捕捉学习任务的共同结构的方式学习表示，同时允许学习者有足够的灵活性来适应新任务的新方面。我们提出了一个基于泛化误差范围的元学习框架，使我们能够扩展各种PAC-Bayes范围到元学习。通过建立基于观察到的任务的假设分布和其用于学习新任务的学习。因此，先前的知识是通过为新任务设置经验依赖的先验而并入的。我们开发了一种基于梯度的算法，该算法将从边界导出的目标函数最小化，并用深度神经网络数值化地证明其有效性。除了通过元学习提供改进的性能之外，我们还展示了先验信息在网络不同层次上表现出来的直观方式。

##### URL
[http://arxiv.org/abs/1711.01244](http://arxiv.org/abs/1711.01244)

##### PDF
[http://arxiv.org/pdf/1711.01244](http://arxiv.org/pdf/1711.01244)

