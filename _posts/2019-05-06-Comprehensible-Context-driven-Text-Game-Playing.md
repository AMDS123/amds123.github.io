---
layout: post
title: "Comprehensible Context-driven Text Game Playing"
date: 2019-05-06 21:14:41
categories: arXiv_CL
tags: arXiv_CL CNN RNN
author: Xusen Yin, Jonathan May
mathjax: true
---

* content
{:toc}

##### Abstract
In order to train a computer agent to play a text-based computer game, we must represent each hidden state of the game. A Long Short-Term Memory (LSTM) model runs over observed texts is a common choice for state construction. However, a normal Deep Q-learning Network (DQN) for such an agent requires millions of steps of training or more to converge. As such, an LSTM-based DQN can take tens of days to finish the training process. Though we can use a Convolution Neural Network (CNN) as a text-encoder to construct states much faster than the LSTM, doing so without an understanding of the syntactic context of the words being analyzed can slow convergence. In this paper, we use a fast CNN to encode position- and syntax-oriented structures extracted from observed texts as states. We additionally augment the reward signal in a universal and practical manner. Together, we show that our improvements can not only speed up the process by one order of magnitude but also learn a superior agent.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02265](https://arxiv.org/abs/1905.02265)

##### PDF
[https://arxiv.org/pdf/1905.02265](https://arxiv.org/pdf/1905.02265)

