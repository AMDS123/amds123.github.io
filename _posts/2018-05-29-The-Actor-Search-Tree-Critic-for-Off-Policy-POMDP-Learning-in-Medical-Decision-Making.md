---
layout: post
title: "The Actor Search Tree Critic for Off-Policy POMDP Learning in Medical Decision Making"
date: 2018-05-29 15:55:33
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Luchen Li, Matthieu Komorowski, Aldo A. Faisal
mathjax: true
---

* content
{:toc}

##### Abstract
Off-policy reinforcement learning enables near-optimal policy from suboptimal experience, thereby provisions opportunity for artificial intelligence applications in healthcare. Previous works have mainly framed patient-clinician interactions as Markov decision processes, while true physiological states are not necessarily fully observable from clinical data. We capture this situation with partially observable Markov decision process, in which an agent optimises its actions in a belief represented as a distribution of patient states inferred from individual history trajectories. A Gaussian mixture model is fitted for the observed data. Moreover, we take into account the fact that nuance in pharmaceutical dosage could presumably result in significantly different effect by modelling a continuous policy through a Gaussian approximator directly in the policy space, i.e. the actor. To address the challenge of infinite number of possible belief states which renders exact value iteration intractable, we evaluate and plan for only every encountered belief, through heuristic search tree by tightly maintaining lower and upper bounds of the true value of belief. We further resort to function approximations to update value bounds estimation, i.e. the critic, so that the tree search can be improved through more compact bounds at the fringe nodes that will be back-propagated to the root. Both actor and critic parameters are learned via gradient-based approaches. Our proposed policy trained from real intensive care unit data is capable of dictating dosing on vasopressors and intravenous fluids for sepsis patients that lead to the best patient outcomes.

##### Abstract (translated by Google)
非政策强化学习能够通过次优体验实现接近最优的策略，从而为人工智能应用在医疗保健方面提供机会。以前的研究主要将患者 - 临床医生的交互作为马尔可夫决策过程进行框架化，而真正的生理状态不一定能从临床数据中完全观察到。我们用部分可观察的马尔可夫决策过程来捕捉这种情况，其中一个智能体在一个信念中优化了它的行为，这个信念表示为从个体历史轨迹推断的病人状态分布。对观测数据拟合高斯混合模型。此外，我们考虑到这样的事实，即通过直接在策略空间即演员中通过高斯逼近器对连续策略进行建模，药物剂量中的细微差别可能导致显着不同的效果。为了解决无限数量的可能的信念状态的挑战，其使得精确值迭代难以处理，我们通过启发式搜索树通过紧密维持信念真值的上限和下限来评估和计划每个遇到的信念。我们进一步求助于函数逼近来更新值边界估计，即批评，从而通过边缘节点处更加紧凑的边界来改进树搜索，所述边界将被反向传播到根。演员和评论者参数都是通过基于渐变的方法学习的。我们根据真正的重症监护病房数据训练的建议政策能够为导致最佳患者结局的败血症患者指定血管加压剂和静脉输液。

##### URL
[http://arxiv.org/abs/1805.11548](http://arxiv.org/abs/1805.11548)

##### PDF
[http://arxiv.org/pdf/1805.11548](http://arxiv.org/pdf/1805.11548)

