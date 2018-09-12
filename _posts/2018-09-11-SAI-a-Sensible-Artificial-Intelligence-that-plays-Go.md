---
layout: post
title: "SAI, a Sensible Artificial Intelligence that plays Go"
date: 2018-09-11 14:30:01
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Francesco Morandin, Gianluca Amato, Rosa Gini, Carlo Metta, Maurizio Parton, Gian-Carlo Pascutto
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a multiple-komi modification of the AlphaGo Zero/Leela Zero paradigm. The winrate as a function of the komi is modeled with a two-parameters sigmoid function, so that the neural network must predict just one more variable to assess the winrate for all komi values. A second novel feature is that training is based on self-play games that occasionaly branch -with changed komi- when the position is uneven. With this setting, reinforcement learning is showed to work on 7x7 Go, obtaining very strong playing agents. As a useful byproduct, the sigmoid parameters given by the network allow to estimate the score difference on the board, and to evaluate how much the game is decided.

##### Abstract (translated by Google)
我们提出了AlphaGo Zero / Leela Zero范例的多元修改。作为komi函数的winrate是用双参数sigmoid函数建模的，因此神经网络必须预测另外一个变量来评估所有komi值的winrate。第二个新颖的特征是训练是基于自我玩游戏，偶尔分支 - 当位置不均匀时改变komi-。通过这种设置，强化学习可以在7x7 Go上运行，获得非常强大的游戏代理。作为有用的副产品，网络给出的S形参数允许估计棋盘上的得分差异，并评估决定游戏的程度。

##### URL
[http://arxiv.org/abs/1809.03928](http://arxiv.org/abs/1809.03928)

##### PDF
[http://arxiv.org/pdf/1809.03928](http://arxiv.org/pdf/1809.03928)

