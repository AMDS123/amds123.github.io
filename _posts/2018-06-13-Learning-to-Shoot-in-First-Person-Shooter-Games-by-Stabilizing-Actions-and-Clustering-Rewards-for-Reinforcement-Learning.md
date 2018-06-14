---
layout: post
title: "Learning to Shoot in First Person Shooter Games by Stabilizing Actions and Clustering Rewards for Reinforcement Learning"
date: 2018-06-13 15:41:34
categories: arXiv_AI
tags: arXiv_AI Attention Reinforcement_Learning
author: Frank G. Glavin, Michael G. Madden
mathjax: true
---

* content
{:toc}

##### Abstract
While reinforcement learning (RL) has been applied to turn-based board games for many years, more complex games involving decision-making in real-time are beginning to receive more attention. A challenge in such environments is that the time that elapses between deciding to take an action and receiving a reward based on its outcome can be longer than the interval between successive decisions. We explore this in the context of a non-player character (NPC) in a modern first-person shooter game. Such games take place in 3D environments where players, both human and computer-controlled, compete by engaging in combat and completing task objectives. We investigate the use of RL to enable NPCs to gather experience from game-play and improve their shooting skill over time from a reward signal based on the damage caused to opponents. We propose a new method for RL updates and reward calculations, in which the updates are carried out periodically, after each shooting encounter has ended, and a new weighted-reward mechanism is used which increases the reward applied to actions that lead to damaging the opponent in successive hits in what we term "hit clusters".

##### Abstract (translated by Google)
虽然强化学习（RL）已经应用于基于回合的棋盘游戏多年，但更复杂的涉及实时决策的游戏开始受到更多关注。这种环境中的一个挑战是，在决定采取行动和根据其结果接受奖励之间所经过的时间可能比连续决定之间的间隔更长。我们在现代第一人称射击游戏中的非玩家角色（NPC）中探索这一点。这类游戏发生在3D环境中，玩家既是人类又是计算机控制的，通过参与战斗和完成任务目标进行竞争。我们调查了RL的使用，使NPC能够从游戏中收集经验，并根据对对手造成的伤害的奖励信号提高他们的射击技能。我们提出了一种RL更新和奖励计算的新方法，其中在每次拍摄相遇结束后定期进行更新，并且使用新的加权奖励机制，该机制增加用于导致损害对手的动作的奖励连续击中我们称之为“命中的群集”。

##### URL
[http://arxiv.org/abs/1806.05117](http://arxiv.org/abs/1806.05117)

##### PDF
[http://arxiv.org/pdf/1806.05117](http://arxiv.org/pdf/1806.05117)

