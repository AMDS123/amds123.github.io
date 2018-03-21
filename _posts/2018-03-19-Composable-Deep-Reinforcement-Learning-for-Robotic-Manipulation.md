---
layout: post
title: "Composable Deep Reinforcement Learning for Robotic Manipulation"
date: 2018-03-19 01:17:16
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Tuomas Haarnoja, Vitchyr Pong, Aurick Zhou, Murtaza Dalal, Pieter Abbeel, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Model-free deep reinforcement learning has been shown to exhibit good performance in domains ranging from video games to simulated robotic manipulation and locomotion. However, model-free methods are known to perform poorly when the interaction time with the environment is limited, as is the case for most real-world robotic tasks. In this paper, we study how maximum entropy policies trained using soft Q-learning can be applied to real-world robotic manipulation. The application of this method to real-world manipulation is facilitated by two important features of soft Q-learning. First, soft Q-learning can learn multimodal exploration strategies by learning policies represented by expressive energy-based models. Second, we show that policies learned with soft Q-learning can be composed to create new policies, and that the optimality of the resulting policy can be bounded in terms of the divergence between the composed policies. This compositionality provides an especially valuable tool for real-world manipulation, where constructing new policies by composing existing skills can provide a large gain in efficiency over training from scratch. Our experimental evaluation demonstrates that soft Q-learning is substantially more sample efficient than prior model-free deep reinforcement learning methods, and that compositionality can be performed for both simulated and real-world tasks.

##### Abstract (translated by Google)
无模型深度强化学习已被证明在视频游戏，模拟机器人操纵和运动等领域表现出色。然而，无模型方法在与环境的交互时间有限的情况下表现不佳，正如大多数现实世界中的机器人任务一样。在本文中，我们研究了如何将使用软Q学习训练的最大熵策略应用于真实世界的机器人操纵。这种方法在现实世界中的应用可以通过软Q学习的两个重要特征来促进。首先，软Q学习可以通过学习以表达能源模型为代表的政策来学习多模式探索策略。其次，我们展示了用软Q学习学习的政策可以组成新政策，并且由此产生的政策的最优性可以根据合成政策之间的差异来界定。这种组合性为真实世界的操作提供了一个特别有价值的工具，通过组合现有技能来构建新的策略，可以从无到有的提高培训效率。我们的实验评估表明，软Q学习比先前的无模型深层强化学习方法更有效，并且可以对模拟和现实世界任务执行组合性。

##### URL
[https://arxiv.org/abs/1803.06773](https://arxiv.org/abs/1803.06773)

##### PDF
[https://arxiv.org/pdf/1803.06773](https://arxiv.org/pdf/1803.06773)

