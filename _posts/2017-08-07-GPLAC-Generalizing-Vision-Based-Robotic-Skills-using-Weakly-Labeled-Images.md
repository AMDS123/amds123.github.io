---
layout: post
title: "GPLAC: Generalizing Vision-Based Robotic Skills using Weakly Labeled Images"
date: 2017-08-07 21:34:59
categories: arXiv_CV
tags: arXiv_CV Attention Reinforcement_Learning CNN Classification
author: Avi Singh, Larry Yang, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of learning robotic sensorimotor control policies that can generalize to visually diverse and unseen environments. Achieving broad generalization typically requires large datasets, which are difficult to obtain for task-specific interactive processes such as reinforcement learning or learning from demonstration. However, much of the visual diversity in the world can be captured through passively collected datasets of images or videos. In our method, which we refer to as GPLAC (Generalized Policy Learning with Attentional Classifier), we use both interaction data and weakly labeled image data to augment the generalization capacity of sensorimotor policies. Our method combines multitask learning on action selection and an auxiliary binary classification objective, together with a convolutional neural network architecture that uses an attentional mechanism to avoid distractors. We show that pairing interaction data from just a single environment with a diverse dataset of weakly labeled data results in greatly improved generalization to unseen environments, and show that this generalization depends on both the auxiliary objective and the attentional architecture that we propose. We demonstrate our results in both simulation and on a real robotic manipulator, and demonstrate substantial improvement over standard convolutional architectures and domain adaptation methods.

##### Abstract (translated by Google)
我们解决了学习机器人感觉运动控制策略的问题，该策略可以推广到视觉多样和看不见的环境。实现广义的泛化通常需要大数据集，这对于特定于任务的交互过程（如强化学习或示范学习）很难获得。然而，世界上的许多视觉多样性可以通过被动收集的图像或视频数据集来捕捉。在我们称之为GPLAC（具有注意力分类器的广义策略学习）的方法中，我们使用交互数据和弱标记的图像数据来增强感觉运动策略的泛化能力。我们的方法将动作选择的多任务学习和辅助二元分类目标结合起来，以及使用注意机制避免分心的卷积神经网络架构。我们展示了来自单一环境的配对交互数据与具有弱标记数据的不同数据集导致对于看不见的环境的泛化大大改善，并且表明这种泛化取决于我们提出的辅助目标和注意力架构。我们在仿真和真正的机器人操纵器上展示了我们的结果，并且证明了在标准卷积架构和领域适应方法方面的实质性改进。

##### URL
[https://arxiv.org/abs/1708.02313](https://arxiv.org/abs/1708.02313)

##### PDF
[https://arxiv.org/pdf/1708.02313](https://arxiv.org/pdf/1708.02313)

