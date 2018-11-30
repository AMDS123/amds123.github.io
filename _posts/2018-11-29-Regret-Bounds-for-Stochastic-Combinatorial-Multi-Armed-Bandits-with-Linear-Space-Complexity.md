---
layout: post
title: "Regret Bounds for Stochastic Combinatorial Multi-Armed Bandits with Linear Space Complexity"
date: 2018-11-29 02:12:37
categories: arXiv_AI
tags: arXiv_AI Face
author: Mridul Agarwal, Vaneet Aggarwal
mathjax: true
---

* content
{:toc}

##### Abstract
Many real-world problems face the dilemma of choosing best $K$ out of $N$ options at a given time instant. This setup can be modelled as combinatorial bandit which chooses $K$ out of $N$ arms at each time, with an aim to achieve an efficient tradeoff between exploration and exploitation. This is the first work for combinatorial bandit where the reward received can be a non-linear function of the chosen $K$ arms. The direct use of multi-armed bandit requires choosing among $N$-choose-$K$ options making the state space large. In this paper, we present a novel algorithm which is computationally efficient and the storage is linear in $N$. The proposed algorithm is a divide-and-conquer based strategy, that we call CMAB-SM. Further, the proposed algorithm achieves a regret bound of $\tilde O(K^\frac{1}{2}N^\frac{1}{3}T^\frac{2}{3})$ for a time horizon $T$, which is sub-linear in all parameters $T$, $N$, and $K$. The evaluation results on different reward functions and arm distribution functions show significantly improved performance as compared to standard multi-armed bandit approach with $\binom{N}{K}$ choices.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11925](http://arxiv.org/abs/1811.11925)

##### PDF
[http://arxiv.org/pdf/1811.11925](http://arxiv.org/pdf/1811.11925)

