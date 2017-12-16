---
layout: post
title: "Time-Contrastive Networks: Self-Supervised Learning from Video"
date: 2017-10-06 01:26:56
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Embedding Relation
author: Pierre Sermanet, Corey Lynch, Yevgen Chebotar, Jasmine Hsu, Eric Jang, Stefan Schaal, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a self-supervised approach for learning representations and robotic behaviors entirely from unlabeled videos recorded from multiple viewpoints, and study how this representation can be used in two robotic imitation settings: imitating object interactions from videos of humans, and imitating human poses. Imitation of human behavior requires a viewpoint-invariant representation that captures the relationships between end-effectors (hands or robot grippers) and the environment, object attributes, and body pose. We train our representations using a triplet loss, where multiple simultaneous viewpoints of the same observation are attracted in the embedding space, while being repelled from temporal neighbors which are often visually similar but functionally different. This signal causes our model to discover attributes that do not change across viewpoint, but do change across time, while ignoring nuisance variables such as occlusions, motion blur, lighting and background. We demonstrate that this representation can be used by a robot to directly mimic human poses without an explicit correspondence, and that it can be used as a reward function within a reinforcement learning algorithm. While representations are learned from an unlabeled collection of task-related videos, robot behaviors such as pouring are learned by watching a single 3rd-person demonstration by a human. Reward functions obtained by following the human demonstrations under the learned representation enable efficient reinforcement learning that is practical for real-world robotic systems. Video results, open-source code and dataset are available at this https URL

##### Abstract (translated by Google)
我们提出了一个自我监督的方法来学习表示和机器人行为完全从多个角度记录的无标签的视频，并研究如何在两个机器人模仿设置中使用这种表示：模仿人类视频的对象交互和模仿人类的姿势。模仿人类行为需要一个观点不变的表示，捕捉末端执行者（双手或机器人手爪）与环境，对象属性和身体姿势之间的关系。我们使用三重损失来训练我们的表示，其中在嵌入空间中同时观察到多个同时观察点，同时被时间邻居排斥，这些临时邻居通常在视觉上相似但在功能上不同。这个信号使得我们的模型能够发现在视点之间不会改变的属性，但是会随着时间而改变，而忽略遮挡，运动模糊，光照和背景等干扰变量。我们证明这种表示可以被机器人用来直接模仿人类的姿势而没有明确的对应关系，并且它可以用作强化学习算法中的奖励函数。虽然从没有标签的任务相关视频集合中学习表示，但是通过观看人类的单个第三人示范来学习倾倒等机器人行为。通过学习表示下的人类示范获得的奖励功能可以实现对现实世界中的机器人系统实用的高效强化学习。视频结果，开源代码和数据集可在此https网址上获得

##### URL
[https://arxiv.org/abs/1704.06888](https://arxiv.org/abs/1704.06888)

##### PDF
[https://arxiv.org/pdf/1704.06888](https://arxiv.org/pdf/1704.06888)

