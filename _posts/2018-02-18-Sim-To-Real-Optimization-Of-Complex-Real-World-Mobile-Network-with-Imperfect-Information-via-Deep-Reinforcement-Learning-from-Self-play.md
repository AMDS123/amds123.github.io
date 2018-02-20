---
layout: post
title: "Sim-To-Real Optimization Of Complex Real World Mobile Network with Imperfect Information via Deep Reinforcement Learning from Self-play"
date: 2018-02-18 18:03:39
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Relation
author: Yongxi Tan, Jin Yang, Xin Chen, Qitao Song, Yunjun Chen, Zhangxiang Ye, Zhenqiang Su
mathjax: true
---

* content
{:toc}

##### Abstract
Mobile network that millions of people use every day is one of the most complex systems in real world. Optimization of mobile network to meet exploding customer demand and reduce CAPEX/OPEX poses greater challenges than in prior works. Learning to solve complex problems in real world to benefit everyone and make the world better has long been ultimate goal of AI. However, it still remains an unsolved problem for deep reinforcement learning (DRL), given imperfect information in real world, huge state/action space, lots of data needed for training, associated time/cost, multi-agent interactions, potential negative impact to real world, etc. To bridge this reality gap, we proposed a DRL framework to direct transfer optimal policy learned from multi-tasks in source domain to unseen similar tasks in target domain without any further training in both domains. First, we distilled temporal-spatial relationships between cells and mobile users to scalable 3D image-like tensor to best characterize partially observed mobile network. Second, inspired by AlphaGo, we used a novel self-play mechanism to empower DRL agent to gradually improve its intelligence by competing for best record on multiple tasks. Third, a decentralized DRL method is proposed to coordinate multi-agents to compete and cooperate as a team to maximize global reward and minimize potential negative impact. Using 7693 unseen test tasks over 160 unseen simulated mobile networks and 6 field trials over 4 commercial mobile networks in real world, we demonstrated the capability of our approach to direct transfer the learning from one simulator to another simulator, and from simulation to real world. This is the first time that a DRL agent successfully transfers its learning directly from simulation to very complex real world problems with incomplete and imperfect information, huge state/action space and multi-agent interactions.

##### Abstract (translated by Google)
每天有数百万人使用的移动网络是现实世界中最复杂的系统之一。移动网络的优化以满足爆炸性客户需求并降低CAPEX / OPEX带来比以前的工作更大的挑战。学习解决现实世界中的复杂问题，让每个人都受益并让世界变得更美好，这一直是人工智能的终极目标。然而，对于深度强化学习（DRL），鉴于现实世界中的信息不完善，巨大的状态/行为空间，训练所需的大量数据，相关时间/成本，多主体相互作用以及潜在的负面影响，它仍然是未解决的问题为了弥补这种现实差距，我们提出了一个DRL框架，将从源域中的多任务学习到的转移最优策略直接转移到目标域中看不到的类似任务，而无需在这两个域中进行任何进一步的培训。首先，我们将小区和移动用户之间的时空关系提取为可扩展的3D图像样张量，以最好地表征部分观察到的移动网络。其次，在AlphaGo的启发下，我们使用了一种新颖的自我激励机制，让DRL代理通过争夺多项任务的最佳记录来逐步提高其智能。第三，提出了一种分散DRL方法来协调多个代理商作为一个团队进行竞争和合作，以最大限度地获得全球报酬并最大限度地减少潜在的负面影响。我们在现实世界中使用了超过160个未见过的模拟移动网络上的7693个看不见的测试任务，并在4个商业移动网络上进行了6个现场测试，展示了我们的方法能够将学习从一个模拟器直接传输到另一个模拟器，并从模拟到现实世界。这是DRL代理首次成功地将其学习直接从模拟转移到具有不完整和不完整信息，巨大的状态/动作空间和多代理交互的非常复杂的现实世界问题。

##### URL
[http://arxiv.org/abs/1802.06416](http://arxiv.org/abs/1802.06416)

##### PDF
[http://arxiv.org/pdf/1802.06416](http://arxiv.org/pdf/1802.06416)

