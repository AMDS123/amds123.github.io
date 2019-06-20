---
layout: post
title: "Adapting Behaviour via Intrinsic Reward: A Survey and Empirical Study"
date: 2019-06-19 01:07:12
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Survey Represenation_Learning Prediction
author: Cam Linke, Nadia M. Ady, Martha White, Thomas Degris, Adam White
mathjax: true
---

* content
{:toc}

##### Abstract
Learning about many things can provide numerous benefits to a reinforcement learning system. For example, learning many auxiliary value functions, in addition to optimizing the environmental reward, appears to improve both exploration and representation learning. The question we tackle in this paper is how to sculpt the stream of experience---how to adapt the system's behaviour---to optimize the learning of a collection of value functions. A simple answer is to compute an intrinsic reward based on the statistics of each auxiliary learner, and use reinforcement learning to maximize that intrinsic reward. Unfortunately, implementing this simple idea has proven difficult, and thus has been the focus of decades of study. It remains unclear which of the many possible measures of learning would work well in a parallel learning setting where environmental reward is extremely sparse or absent. In this paper, we investigate and compare different intrinsic reward mechanisms in a new bandit-like parallel-learning testbed. We discuss the interaction between reward and prediction learners and highlight the importance of introspective prediction learners: those that increase their rate of learning when progress is possible, and decrease when it is not. We provide a comprehensive empirical comparison of 15 different rewards, including well-known ideas from reinforcement learning and active learning. Our results highlight a simple but seemingly powerful principle: intrinsic rewards based on the amount of learning can generate useful behaviour, if each individual learner is introspective.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07865](http://arxiv.org/abs/1906.07865)

##### PDF
[http://arxiv.org/pdf/1906.07865](http://arxiv.org/pdf/1906.07865)

