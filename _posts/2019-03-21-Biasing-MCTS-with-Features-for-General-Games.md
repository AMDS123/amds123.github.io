---
layout: post
title: "Biasing MCTS with Features for General Games"
date: 2019-03-21 12:09:27
categories: arXiv_AI
tags: arXiv_AI
author: Dennis J. N. J. Soemers, &#xc9;ric Piette, Cameron Browne
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes using a linear function approximator, rather than a deep neural network (DNN), to bias a Monte Carlo tree search (MCTS) player for general games. This is unlikely to match the potential raw playing strength of DNNs, but has advantages in terms of generality, interpretability and resources (time and hardware) required for training. Features describing local patterns are used as inputs. The features are formulated in such a way that they are easily interpretable and applicable to a wide range of general games, and might encode simple local strategies. We gradually create new features during the same self-play training process used to learn feature weights. We evaluate the playing strength of an MCTS player biased by learnt features against a standard upper confidence bounds for trees (UCT) player in multiple different board games, and demonstrate significantly improved playing strength in the majority of them after a small number of self-play training games.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08942](http://arxiv.org/abs/1903.08942)

##### PDF
[http://arxiv.org/pdf/1903.08942](http://arxiv.org/pdf/1903.08942)

