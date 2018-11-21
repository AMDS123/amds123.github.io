---
layout: post
title: "Model Learning for Look-ahead Exploration in Continuous Control"
date: 2018-11-20 06:11:26
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Arpit Agarwal, Katharina Muelling, Katerina Fragkiadaki
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an exploration method that incorporates look-ahead search over basic learnt skills and their dynamics, and use it for reinforcement learning (RL) of manipulation policies . Our skills are multi-goal policies learned in isolation in simpler environments using existing multigoal RL formulations, analogous to options or macroactions. Coarse skill dynamics, i.e., the state transition caused by a (complete) skill execution, are learnt and are unrolled forward during lookahead search. Policy search benefits from temporal abstraction during exploration, though itself operates over low-level primitive actions, and thus the resulting policies does not suffer from suboptimality and inflexibility caused by coarse skill chaining. We show that the proposed exploration strategy results in effective learning of complex manipulation policies faster than current state-of-the-art RL methods, and converges to better policies than methods that use options or parametrized skills as building blocks of the policy itself, as opposed to guiding exploration. We show that the proposed exploration strategy results in effective learning of complex manipulation policies faster than current state-of-the-art RL methods, and converges to better policies than methods that use options or parameterized skills as building blocks of the policy itself, as opposed to guiding exploration.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08086](http://arxiv.org/abs/1811.08086)

##### PDF
[http://arxiv.org/pdf/1811.08086](http://arxiv.org/pdf/1811.08086)

