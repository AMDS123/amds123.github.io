---
layout: post
title: "A Scalable Approach to Multi-Context Continual Learning via Lifelong Skill Encoding"
date: 2018-05-25 20:24:45
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Blake Camp, Jaya Krishna Mandivarapu, Rolando Estrada
mathjax: true
---

* content
{:toc}

##### Abstract
Continual or lifelong learning (CL) is one of the most challenging problems in machine learning. In this paradigm, a system must learn new tasks, contexts, or data without forgetting previously learned information. We present a scalable approach to multi-context continual learning (MCCL) in which we decouple how a system learns to solve new tasks (i.e., acquires skills) from how it stores them. Our approach leverages two types of artificial networks: (1) a set of reusable, \textit{task-specific networks} (TN) that can be trained as needed to learn new skills, and (2) a lifelong, \textit{autoencoder network} (EN) that stores all learned skills in a compact, latent space. To learn a new skill, we first train a TN using conventional backpropagation, thus placing no restrictions on the system's ability to encode the new task. We then incorporate the newly learned skill into the latent space by first recalling previously learned skills using our EN and then retraining it on both the new and recalled skills. Our approach can efficiently store an arbitrary number of skills without compromising previously learned information because each skill is stored as a separate latent vector. Whenever a particular skill is needed, we recall the necessary weights using our EN and then load them into the corresponding TN. Experiments on the MNIST and CIFAR datasets show that we can continually learn new skills without compromising the performance of existing skills. To the best of our knowledge, we are the first to demonstrate the feasibility of encoding entire networks in order to facilitate efficient continual learning.

##### Abstract (translated by Google)
持续或终身学习（CL）是机器学习中最具挑战性的问题之一。在这种模式下，系统必须学习新的任务，上下文或数据，而不会忘记以前学过的信息。我们提出了一种多环境连续学习（MCCL）的可扩展方法，在这种方法中，我们分解了系统学习如何解决新任务（即获取技能）与存储它们的方式。我们的方法利用两种类型的人工网络：（1）一组可重复使用的\ textit {任务特定网络}（TN），可根据需要进行培训以学习新技能;（2）终身的\ textit {autoencoder网络}（EN），将所有学过的技能存储在一个紧凑的，潜在的空间中。为了学习新技能，我们首先使用传统反向传播训练TN，因此对系统编码新任务的能力没有限制。然后，我们将新学到的技能融入潜在空间，首先回顾先前使用我们的EN学到的技能，然后对新技能和召回技能进行再培训。我们的方法可以高效地存储任意数量的技能，而不会影响以前学到的信息，因为每项技能都是作为单独的潜在向量存储的。无论何时需要特定技能，我们都会使用我们的EN回忆必要的重量，然后将它们加载到相应的TN中。 MNIST和CIFAR数据集上的实验表明，我们可以不断学习新技能，而不会影响现有技能的表现。就我们所知，我们首先证明了编码整个网络的可行性，以促进高效的持续学习。

##### URL
[http://arxiv.org/abs/1805.10354](http://arxiv.org/abs/1805.10354)

##### PDF
[http://arxiv.org/pdf/1805.10354](http://arxiv.org/pdf/1805.10354)

