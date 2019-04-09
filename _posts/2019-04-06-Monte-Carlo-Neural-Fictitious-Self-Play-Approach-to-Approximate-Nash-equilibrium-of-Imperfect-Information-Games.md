---
layout: post
title: "Monte Carlo Neural Fictitious Self-Play: Approach to Approximate Nash equilibrium of Imperfect-Information Games"
date: 2019-04-06 09:12:25
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Li Zhang, Wei Wang, Shijian Li, Gang Pan
mathjax: true
---

* content
{:toc}

##### Abstract
Researchers on artificial intelligence have achieved human-level intelligence in large-scale perfect-information games, but it is still a challenge to achieve (nearly) optimal results (in other words, an approximate Nash Equilibrium) in large-scale imperfect-information games (i.e. war games, football coach or business strategies). Neural Fictitious Self Play (NFSP) is an effective algorithm for learning approximate Nash equilibrium of imperfect-information games from self-play without prior domain knowledge. However, it relies on Deep Q-Network, which is off-line and is hard to converge in online games with changing opponent strategy, so it can't approach approximate Nash equilibrium in games with large search scale and deep search depth. In this paper, we propose Monte Carlo Neural Fictitious Self Play (MC-NFSP), an algorithm combines Monte Carlo tree search with NFSP, which greatly improves the performance on large-scale zero-sum imperfect-information games. Experimentally, we demonstrate that the proposed Monte Carlo Neural Fictitious Self Play can converge to approximate Nash equilibrium in games with large-scale search depth while the Neural Fictitious Self Play can't. Furthermore, we develop Asynchronous Neural Fictitious Self Play (ANFSP). It use asynchronous and parallel architecture to collect game experience. In experiments, we show that parallel actor-learners have a further accelerated and stabilizing effect on training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09569](http://arxiv.org/abs/1903.09569)

##### PDF
[http://arxiv.org/pdf/1903.09569](http://arxiv.org/pdf/1903.09569)

