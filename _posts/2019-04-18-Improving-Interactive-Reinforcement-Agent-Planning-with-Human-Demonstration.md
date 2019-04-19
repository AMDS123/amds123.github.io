---
layout: post
title: "Improving Interactive Reinforcement Agent Planning with Human Demonstration"
date: 2019-04-18 07:45:36
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Guangliang Li, Randy Gomez, Keisuke Nakamura, Jinying Lin, Qilei Zhang, Bo He
mathjax: true
---

* content
{:toc}

##### Abstract
TAMER has proven to be a powerful interactive reinforcement learning method for allowing ordinary people to teach and personalize autonomous agents' behavior by providing evaluative feedback. However, a TAMER agent planning with UCT---a Monte Carlo Tree Search strategy, can only update states along its path and might induce high learning cost especially for a physical robot. In this paper, we propose to drive the agent's exploration along the optimal path and reduce the learning cost by initializing the agent's reward function via inverse reinforcement learning from demonstration. We test our proposed method in the RL benchmark domain---Grid World---with different discounts on human reward. Our results show that learning from demonstration can allow a TAMER agent to learn a roughly optimal policy up to the deepest search and encourage the agent to explore along the optimal path. In addition, we find that learning from demonstration can improve the learning efficiency by reducing total feedback, the number of incorrect actions and increasing the ratio of correct actions to obtain an optimal policy, allowing a TAMER agent to converge faster.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08621](http://arxiv.org/abs/1904.08621)

##### PDF
[http://arxiv.org/pdf/1904.08621](http://arxiv.org/pdf/1904.08621)

