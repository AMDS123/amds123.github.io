---
layout: post
title: "Rethinking the Discount Factor in Reinforcement Learning: A Decision Theoretic Approach"
date: 2019-02-08 00:30:53
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Silviu Pitis
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning (RL) agents have traditionally been tasked with maximizing the value function of a Markov decision process (MDP), either in continuous settings, with fixed discount factor $\gamma &lt; 1$, or in episodic settings, with $\gamma = 1$. While this has proven effective for specific tasks with well-defined objectives (e.g., games), it has never been established that fixed discounting is suitable for general purpose use (e.g., as a model of human preferences). This paper characterizes rationality in sequential decision making using a set of seven axioms and arrives at a form of discounting that generalizes traditional fixed discounting. In particular, our framework admits a state-action dependent "discount" factor that is not constrained to be less than 1, so long as there is eventual long run discounting. Although this broadens the range of possible preference structures in continuous settings, we show that there exists a unique "optimizing MDP" with fixed $\gamma &lt; 1$ whose optimal value function matches the true utility of the optimal policy, and we quantify the difference between value and utility for suboptimal policies. Our work can be seen as providing a normative justification for (a slight generalization of) Martha White's RL task formalism (2017) and other recent departures from the traditional RL, and is relevant to task specification in RL, inverse RL and preference-based RL.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02893](http://arxiv.org/abs/1902.02893)

##### PDF
[http://arxiv.org/pdf/1902.02893](http://arxiv.org/pdf/1902.02893)

