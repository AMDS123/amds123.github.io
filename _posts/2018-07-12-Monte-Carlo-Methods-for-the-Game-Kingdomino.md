---
layout: post
title: "Monte Carlo Methods for the Game Kingdomino"
date: 2018-07-12 08:07:21
categories: arXiv_AI
tags: arXiv_AI
author: Magnus Gedda, Mikael Z. Lagerkvist, Martin Butler
mathjax: true
---

* content
{:toc}

##### Abstract
Kingdomino is introduced as an interesting game for studying game playing: the game is multiplayer (4 independent players per game); it has a limited game depth (13 moves per player); and it has limited but not insignificant interaction among players. 
 Several strategies based on locally greedy players, Monte Carlo Evaluation (MCE), and Monte Carlo Tree Search (MCTS) are presented with variants. We examine a variation of UCT called progressive win bias and a playout policy (Player-greedy) focused on selecting good moves for the player. A thorough evaluation is done showing how the strategies perform and how to choose parameters given specific time constraints. The evaluation shows that surprisingly MCE is stronger than MCTS for a game like Kingdomino. 
 All experiments use a cloud-native design, with a game server in a Docker container, and agents communicating using a REST-style JSON protocol. This enables a multi-language approach to separating the game state, the strategy implementations, and the coordination layer.

##### Abstract (translated by Google)
Kingdomino是一款用于研究游戏的有趣游戏：游戏是多人游戏（每场4个独立玩家）;它的游戏深度有限（每位玩家13次）;而且玩家之间的互动有限但并非微不足道。
 基于本地贪婪玩家，蒙特卡罗评估（MCE）和蒙特卡罗树搜索（MCTS）的几种策略呈现出变体。我们研究了一种称为渐进式胜利偏见的UCT变体和一种专注于为玩家选择好动作的播出政策（玩家贪婪）。进行全面评估，显示策略如何执行以及如何在给定特定时间限制的情况下选择参数。评估显示，对于像Kingdomino这样的游戏，MCE比MCTS强。
 所有实验都使用云原生设计，Docker容器中有游戏服务器，代理使用REST风格的JSON协议进行通信。这使得多语言方法能够分离游戏状态，策略实现和协调层。

##### URL
[http://arxiv.org/abs/1807.04458](http://arxiv.org/abs/1807.04458)

##### PDF
[http://arxiv.org/pdf/1807.04458](http://arxiv.org/pdf/1807.04458)

