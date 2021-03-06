---
layout: post
title: "Automated Video Game Testing Using Synthetic and Human-Like Agents"
date: 2019-06-02 00:19:00
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Sinan Ariyurek, Aysu Betin-Can, Elif Surer
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a new methodology that employs tester agents to automate video game testing. We introduce two types of agents -synthetic and human-like- and two distinct approaches to create them. Our agents are derived from Reinforcement Learning (RL) and Monte Carlo Tree Search (MCTS) agents, but focus on finding defects. The synthetic agent uses test goals generated from game scenarios, and these goals are further modified to examine the effects of unintended game transitions. The human-like agent uses test goals extracted by our proposed multiple greedy-policy inverse reinforcement learning (MGP-IRL) algorithm from tester trajectories. MGPIRL captures multiple policies executed by human testers. These testers' aims are finding defects while interacting with the game to break it, which is considerably different from game playing. We present interaction states to model such interactions. We use our agents to produce test sequences, run the game with these sequences, and check the game for each run with an automated test oracle. We analyze the proposed method in two parts: we compare the success of human-like and synthetic agents in bug finding, and we evaluate the similarity between humanlike agents and human testers. We collected 427 trajectories from human testers using the General Video Game Artificial Intelligence (GVG-AI) framework and created three games with 12 levels that contain 45 bugs. Our experiments reveal that human-like and synthetic agents compete with human testers' bug finding performances. Moreover, we show that MGP-IRL increases the human-likeness of agents while improving the bug finding performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00317](http://arxiv.org/abs/1906.00317)

##### PDF
[http://arxiv.org/pdf/1906.00317](http://arxiv.org/pdf/1906.00317)

