---
layout: post
title: "Human-level performance in first-person multiplayer games with population-based deep reinforcement learning"
date: 2018-07-03 16:57:18
categories: arXiv_AI
tags: arXiv_AI Sparse Knowledge Reinforcement_Learning
author: Max Jaderberg, Wojciech M. Czarnecki, Iain Dunning, Luke Marris, Guy Lever, Antonio Garcia Castaneda, Charles Beattie, Neil C. Rabinowitz, Ari S. Morcos, Avraham Ruderman, Nicolas Sonnerat, Tim Green, Louise Deason, Joel Z. Leibo, David Silver, Demis Hassabis, Koray Kavukcuoglu, Thore Graepel
mathjax: true
---

* content
{:toc}

##### Abstract
Recent progress in artificial intelligence through reinforcement learning (RL) has shown great success on increasingly complex single-agent environments and two-player turn-based games. However, the real-world contains multiple agents, each learning and acting independently to cooperate and compete with other agents, and environments reflecting this degree of complexity remain an open challenge. In this work, we demonstrate for the first time that an agent can achieve human-level in a popular 3D multiplayer first-person video game, Quake III Arena Capture the Flag, using only pixels and game points as input. These results were achieved by a novel two-tier optimisation process in which a population of independent RL agents are trained concurrently from thousands of parallel matches with agents playing in teams together and against each other on randomly generated environments. Each agent in the population learns its own internal reward signal to complement the sparse delayed reward from winning, and selects actions using a novel temporally hierarchical representation that enables the agent to reason at multiple timescales. During game-play, these agents display human-like behaviours such as navigating, following, and defending based on a rich learned representation that is shown to encode high-level game knowledge. In an extensive tournament-style evaluation the trained agents exceeded the win-rate of strong human players both as teammates and opponents, and proved far stronger than existing state-of-the-art agents. These results demonstrate a significant jump in the capabilities of artificial agents, bringing us closer to the goal of human-level intelligence.

##### Abstract (translated by Google)
通过强化学习（RL）在人工智能方面的最新进展已经在日益复杂的单一代理环境和双人回合制游戏中取得了巨大成功。然而，现实世界包含多个代理，每个代理独立学习和行动以与其他代理进行合作和竞争，反映这种复杂程度的环境仍然是一个开放的挑战。在这项工作中，我们首次证明了一个代理人可以在一个流行的3D多人第一人称视频游戏Quake III Arena Capture the Flag中实现人类级别，仅使用像素和游戏点作为输入。这些结果是通过一种新颖的双层优化过程实现的，其中一组独立的RL代理同时从数千个并行匹配中训练，其中代理在一起玩并且在随机生成的环境中相互对抗。群体中的每个代理人学习其自己的内部奖励信号以补充来自获胜的稀疏延迟奖励，并使用新颖的时间分层表示来选择动作，该动作使得代理能够在多个时间尺度进行推理。在游戏过程中，这些代理基于显示编码高级游戏知识的丰富学习表示来显示类似人的行为，例如导航，跟随和防御。在广泛的锦标赛风格评估中，训练有素的球员超过了作为队友和对手的强大的人类球员的胜利率，并且证明远比现有的最先进的球员更强。这些结果表明人工智能的能力大幅提升，使我们更接近人类智能的目标。

##### URL
[http://arxiv.org/abs/1807.01281](http://arxiv.org/abs/1807.01281)

##### PDF
[http://arxiv.org/pdf/1807.01281](http://arxiv.org/pdf/1807.01281)

