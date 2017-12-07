---
layout: post
title: "Dual Learning for Machine Translation"
date: 2016-11-01 10:38:29
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning NMT
author: Yingce Xia, Di He, Tao Qin, Liwei Wang, Nenghai Yu, Tie-Yan Liu, Wei-Ying Ma
mathjax: true
---

* content
{:toc}

##### Abstract
While neural machine translation (NMT) is making good progress in the past two years, tens of millions of bilingual sentence pairs are needed for its training. However, human labeling is very costly. To tackle this training data bottleneck, we develop a dual-learning mechanism, which can enable an NMT system to automatically learn from unlabeled data through a dual-learning game. This mechanism is inspired by the following observation: any machine translation task has a dual task, e.g., English-to-French translation (primal) versus French-to-English translation (dual); the primal and dual tasks can form a closed loop, and generate informative feedback signals to train the translation models, even if without the involvement of a human labeler. In the dual-learning mechanism, we use one agent to represent the model for the primal task and the other agent to represent the model for the dual task, then ask them to teach each other through a reinforcement learning process. Based on the feedback signals generated during this process (e.g., the language-model likelihood of the output of a model, and the reconstruction error of the original sentence after the primal and dual translations), we can iteratively update the two models until convergence (e.g., using the policy gradient methods). We call the corresponding approach to neural machine translation \emph{dual-NMT}. Experiments show that dual-NMT works very well on English$\leftrightarrow$French translation; especially, by learning from monolingual data (with 10% bilingual data for warm start), it achieves a comparable accuracy to NMT trained from the full bilingual data for the French-to-English translation task.

##### Abstract (translated by Google)
而神经机器翻译（NMT）在过去两年取得了良好的进展，需要数以千万计的双语句对来训练。但是，人的标签是非常昂贵的。为了解决这个训练数据瓶颈，我们开发了一个双重学习机制，使NMT系统能够通过双重学习游戏自动从无标签的数据中学习。这种机制受到以下观察的启发：任何机器翻译任务都有双重任务，例如，英文到法文的翻译（原文）与法文到英文的翻译（双重）;原始和双重任务可以形成一个闭环，并且即使没有人标签的参与，也可以产生信息反馈信号来训练翻译模型。在双重学习机制中，我们使用一个代理来表示原始任务的模型，另一个代理代表双重任务的模型，然后要求他们通过强化学习过程相互传授。基于在这个过程中产生的反馈信号（例如，模型的输出的语言模型可能性，以及在原始和双重平移之后的原始句子的重构误差），我们可以迭代地更新两个模型直到收敛例如，使用策略梯度方法）。我们把相应的方法称为神经机器翻译\ emph {dual-NMT}。实验表明，双NMT在英语$ \ leftrightarrow $法语翻译上效果很好;特别是通过学习单语数据（10％的双语数据用于热启动），与从法语到英语翻译任务的完整双语数据训练的NMT相比，它具有相当的准确性。

##### URL
[https://arxiv.org/abs/1611.00179](https://arxiv.org/abs/1611.00179)

##### PDF
[https://arxiv.org/pdf/1611.00179](https://arxiv.org/pdf/1611.00179)

