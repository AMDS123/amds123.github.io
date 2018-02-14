---
layout: post
title: "CASSL: Curriculum Accelerated Self-Supervised Learning"
date: 2018-02-12 23:24:52
categories: arXiv_CV
tags: arXiv_CV
author: Adithyavairavan Murali, Lerrel Pinto, Dhiraj Gandhi, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Recent self-supervised learning approaches focus on using a few thousand data points to learn policies for high-level, low-dimensional action spaces. However, scaling this framework for high-dimensional control require either scaling up the data collection efforts or using a clever sampling strategy for training. We present a novel approach - Curriculum Accelerated Self-Supervised Learning (CASSL) - to train policies that map visual information to high-level, higher- dimensional action spaces. CASSL orders the sampling of training data based on control dimensions: the learning and sampling are focused on few control parameters before other parameters. The right curriculum for learning is suggested by variance-based global sensitivity analysis of the control space. We apply our CASSL framework to learning how to grasp using an adaptive, underactuated multi-fingered gripper, a challenging system to control. Our experimental results indicate that CASSL provides significant improvement and generalization compared to baseline methods such as staged curriculum learning (8% increase) and complete end-to-end learning with random exploration (14% improvement) tested on a set of novel objects.

##### Abstract (translated by Google)
最近的自我监督学习方法专注于使用几千个数据点来学习高层次，低维度动作空间的策略。然而，扩展高维度控制框架需要扩大数据收集工作或采用巧妙的抽样策略进行培训。我们提出了一种新颖的方法 - 课程加速自我监督学习（CASSL） - 来培训将视觉信息映射到高层次，更高维度的动作空间的策略。 CASSL根据控制维度对训练数据的采样进行排序：学习和采样在其他参数之前集中于少数控制参数。通过对控制空间进行基于方差的全局灵敏度分析，可以提供正确的学习课程。我们将我们的CASSL框架应用于学习如何使用自适应，欠驱动的多指抓取器，一个具有挑战性的系统进行控制。我们的实验结果表明，与基线方法相比，CASSL提供了显着的改进和推广，例如阶段式课程学习（增加8％），并在一组新颖的对象上进行了随机探索（14％改进）的完整端对端学习。

##### URL
[http://arxiv.org/abs/1708.01354](http://arxiv.org/abs/1708.01354)

##### PDF
[http://arxiv.org/pdf/1708.01354](http://arxiv.org/pdf/1708.01354)

