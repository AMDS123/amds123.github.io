---
layout: post
title: "Learning Montezuma's Revenge from a Single Demonstration"
date: 2018-12-08 20:16:16
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Tim Salimans, Richard Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new method for learning from a single demonstration to solve hard exploration tasks like the Atari game Montezuma's Revenge. Instead of imitating human demonstrations, as proposed in other recent works, our approach is to maximize rewards directly. Our agent is trained using off-the-shelf reinforcement learning, but starts every episode by resetting to a state from a demonstration. By starting from such demonstration states, the agent requires much less exploration to learn a game compared to when it starts from the beginning of the game at every episode. We analyze reinforcement learning for tasks with sparse rewards in a simple toy environment, where we show that the run-time of standard RL methods scales exponentially in the number of states between rewards. Our method reduces this to quadratic scaling, opening up many tasks that were previously infeasible. We then apply our method to Montezuma's Revenge, for which we present a trained agent achieving a high-score of 74,500, better than any previously published result.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03381](http://arxiv.org/abs/1812.03381)

##### PDF
[http://arxiv.org/pdf/1812.03381](http://arxiv.org/pdf/1812.03381)

