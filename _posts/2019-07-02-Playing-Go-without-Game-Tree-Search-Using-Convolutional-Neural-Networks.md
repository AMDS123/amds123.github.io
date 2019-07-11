---
layout: post
title: "Playing Go without Game Tree Search Using Convolutional Neural Networks"
date: 2019-07-02 19:12:38
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning CNN
author: Jeffrey Barratt, Chuanbo Pan
mathjax: true
---

* content
{:toc}

##### Abstract
The game of Go has a long history in East Asian countries, but the field of Computer Go has yet to catch up to humans until the past couple of years. While the rules of Go are simple, the strategy and combinatorics of the game are immensely complex. Even within the past couple of years, new programs that rely on neural networks to evaluate board positions still explore many orders of magnitude more board positions per second than a professional can. We attempt to mimic human intuition in the game by creating a convolutional neural policy network which, without any sort of tree search, should play the game at or above the level of most humans. We introduce three structures and training methods that aim to create a strong Go player: non-rectangular convolutions, which will better learn the shapes on the board, supervised learning, training on a data set of 53,000 professional games, and reinforcement learning, training on games played between different versions of the network. Our network has already surpassed the skill level of intermediate amateurs simply using supervised learning. Further training and implementation of non-rectangular convolutions and reinforcement learning will likely increase this skill level much further.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04658](http://arxiv.org/abs/1907.04658)

##### PDF
[http://arxiv.org/pdf/1907.04658](http://arxiv.org/pdf/1907.04658)

