---
layout: post
title: "CASSL: Curriculum Accelerated Self-Supervised Learning"
date: 2017-08-04 02:13:50
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
最近的自我监督学习方法着重于使用几千个数据点来学习高层次，低维度的动作空间的策略。然而，扩展高维度控制的框架要么要么扩大数据收集工作，要么采用聪明的抽样策略进行培训。我们提出了一个新颖的方法 - 课程加速自我监督学习（CASSL） - 培训政策，将视觉信息映射到高层次，更高维度的行动空间。 CASSL根据控制维度对训练数据进行抽样：学习和抽样的重点是其他参数之前的少数控制参数。通过对控制空间进行基于方差的全局灵敏度分析，建议正确的学习课程。我们运用我们的CASSL框架来学习如何使用一个自适应的，欠驱动的多指抓取器，一个具有挑战性的系统来控制。我们的实验结果表明，与基线方法相比，CASSL提供了显着的改进和推广，例如阶段式课程学习（增加8％），以及在一组新颖的对象上进行随机探索（14％改进）的完整端对端学习。

##### URL
[https://arxiv.org/abs/1708.01354](https://arxiv.org/abs/1708.01354)

##### PDF
[https://arxiv.org/pdf/1708.01354](https://arxiv.org/pdf/1708.01354)

