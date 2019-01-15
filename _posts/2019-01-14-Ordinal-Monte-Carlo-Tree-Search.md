---
layout: post
title: "Ordinal Monte Carlo Tree Search"
date: 2019-01-14 13:01:59
categories: arXiv_AI
tags: arXiv_AI
author: Tobias Joppen, Johannes F&#xfc;rnkranz
mathjax: true
---

* content
{:toc}

##### Abstract
In many problem settings, most notably in game playing, an agent receives a possibly delayed reward for its actions. Often, those rewards are handcrafted and not naturally given. Even simple terminal-only rewards, like winning equals 1 and losing equals -1, can not be seen as an unbiased statement, since these values are chosen arbitrarily, and the behavior of the learner may change with different encodings, such as setting the value of a loss to -0:5, which is often done in practice to encourage learning. It is hard to argue about good rewards and the performance of an agent often depends on the design of the reward signal. In particular, in domains where states by nature only have an ordinal ranking and where meaningful distance information between game state values are not available, a numerical reward signal is necessarily biased. In this paper, we take a look at Monte Carlo Tree Search (MCTS), a popular algorithm to solve MDPs, highlight a reoccurring problem concerning its use of rewards, and show that an ordinal treatment of the rewards overcomes this problem. Using the General Video Game Playing framework we show a dominance of our newly proposed ordinal MCTS algorithm over preference-based MCTS, vanilla MCTS and various other MCTS variants.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.04274](http://arxiv.org/abs/1901.04274)

##### PDF
[http://arxiv.org/pdf/1901.04274](http://arxiv.org/pdf/1901.04274)

