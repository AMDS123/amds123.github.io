---
layout: post
title: "Cost Functions for Robot Motion Style"
date: 2018-09-01 01:14:15
categories: arXiv_RO
tags: arXiv_RO Knowledge Optimization
author: Allan Zhou, Anca D. Dragan
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on autonomously generating robot motion for day to day physical tasks that is expressive of a certain style or emotion. Because we seek generalization across task instances and task types, we propose to capture style via cost functions that the robot can use to augment its nominal task cost and task constraints in a trajectory optimization process. We compare two approaches to representing such cost functions: a weighted linear combination of hand-designed features, and a neural network parameterization operating on raw trajectory input. For each cost type, we learn weights for each style from user feedback. We contrast these approaches to a nominal motion across different tasks and for different styles in a user study, and find that they both perform on par with each other, and significantly outperform the baseline. Each approach has its advantages: featurized costs require learning fewer parameters and can perform better on some styles, but neural network representations do not require expert knowledge to design features and could even learn more complex, nuanced costs than an expert can easily design.

##### Abstract (translated by Google)
我们专注于自主生成机器人运动，用于表达某种风格或情感的日常身体任务。因为我们寻求跨任务实例和任务类型的泛化，我们建议通过成本函数捕获样式，机器人可以使用它来增加其在轨迹优化过程中的名义任务成本和任务约束。我们比较了两种表示这种成本函数的方法：手工设计特征的加权线性组合，以及在原始轨迹输入上操作的神经网络参数化。对于每种成本类型，我们从用户反馈中了解每种样式的权重。我们将这些方法与不同任务中的名义运动和用户研究中的不同风格进行对比，发现它们的表现彼此相同，并且明显优于基线。每种方法都有其优点：特征化成本需要学习更少的参数，并且可以在某些样式上表现更好，但神经网络表示不需要专业知识来设计特征，甚至可以学习比专家可以轻松设计的更复杂，更细微的成本。

##### URL
[http://arxiv.org/abs/1809.00092](http://arxiv.org/abs/1809.00092)

##### PDF
[http://arxiv.org/pdf/1809.00092](http://arxiv.org/pdf/1809.00092)

