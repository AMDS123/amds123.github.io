---
layout: post
title: "Multiple Policy Value Monte Carlo Tree Search"
date: 2019-05-31 11:33:06
categories: arXiv_AI
tags: arXiv_AI
author: Li-Cheng Lan, Wei Li, Ting-Han Wei, I-Chen Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Many of the strongest game playing programs use a combination of Monte Carlo tree search (MCTS) and deep neural networks (DNN), where the DNNs are used as policy or value evaluators. Given a limited budget, such as online playing or during the self-play phase of AlphaZero (AZ) training, a balance needs to be reached between accurate state estimation and more MCTS simulations, both of which are critical for a strong game playing agent. Typically, larger DNNs are better at generalization and accurate evaluation, while smaller DNNs are less costly, and therefore can lead to more MCTS simulations and bigger search trees with the same budget. This paper introduces a new method called the multiple policy value MCTS (MPV-MCTS), which combines multiple policy value neural networks (PV-NNs) of various sizes to retain advantages of each network, where two PV-NNs f_S and f_L are used in this paper. We show through experiments on the game NoGo that a combined f_S and f_L MPV-MCTS outperforms single PV-NN with policy value MCTS, called PV-MCTS. Additionally, MPV-MCTS also outperforms PV-MCTS for AZ training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13521](http://arxiv.org/abs/1905.13521)

##### PDF
[http://arxiv.org/pdf/1905.13521](http://arxiv.org/pdf/1905.13521)

