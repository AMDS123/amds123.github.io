---
layout: post
title: "Assessing the Potential of Classical Q-learning in General Game Playing"
date: 2018-10-14 18:49:33
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Deep_Learning
author: Hui Wang, Michael Emmerich, Aske Plaat
mathjax: true
---

* content
{:toc}

##### Abstract
After the recent groundbreaking results of AlphaGo and AlphaZero, we have seen strong interests in deep reinforcement learning and artificial general intelligence (AGI) in game playing. However, deep learning is resource-intensive and the theory is not yet well developed. For small games, simple classical table-based Q-learning might still be the algorithm of choice. General Game Playing (GGP) provides a good testbed for reinforcement learning to research AGI. Q-learning is one of the canonical reinforcement learning methods, and has been used by (Banerjee $\&$ Stone, IJCAI 2007) in GGP. In this paper we implement Q-learning in GGP for three small-board games (Tic-Tac-Toe, Connect Four, Hex)\footnote{source code: this https URL}, to allow comparison to Banerjee et al.. We find that Q-learning converges to a high win rate in GGP. For the $\epsilon$-greedy strategy, we propose a first enhancement, the dynamic $\epsilon$ algorithm. In addition, inspired by (Gelly $\&$ Silver, ICML 2007) we combine online search (Monte Carlo Search) to enhance offline learning, and propose QM-learning for GGP. Both enhancements improve the performance of classical Q-learning. In this work, GGP allows us to show, if augmented by appropriate enhancements, that classical table-based Q-learning can perform well in small games.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.06078](https://arxiv.org/abs/1810.06078)

##### PDF
[https://arxiv.org/pdf/1810.06078](https://arxiv.org/pdf/1810.06078)

