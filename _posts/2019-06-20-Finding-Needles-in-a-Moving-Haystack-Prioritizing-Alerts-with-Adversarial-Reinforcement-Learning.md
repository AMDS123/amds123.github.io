---
layout: post
title: "Finding Needles in a Moving Haystack: Prioritizing Alerts with Adversarial Reinforcement Learning"
date: 2019-06-20 18:47:06
categories: arXiv_AI
tags: arXiv_AI Adversarial Reinforcement_Learning Detection
author: Liang Tong, Aron Laszka, Chao Yan, Ning Zhang, Yevgeniy Vorobeychik
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of malicious behavior is a fundamental problem in security. One of the major challenges in using detection systems in practice is in dealing with an overwhelming number of alerts that are triggered by normal behavior (the so-called false positives), obscuring alerts resulting from actual malicious activity. While numerous methods for reducing the scope of this issue have been proposed, ultimately one must still decide how to prioritize which alerts to investigate, and most existing prioritization methods are heuristic, for example, based on suspiciousness or priority scores. We introduce a novel approach for computing a policy for prioritizing alerts using adversarial reinforcement learning. Our approach assumes that the attackers know the full state of the detection system and dynamically choose an optimal attack as a function of this state, as well as of the alert prioritization policy. The first step of our approach is to capture the interaction between the defender and attacker in a game theoretic model. To tackle the computational complexity of solving this game to obtain a dynamic stochastic alert prioritization policy, we propose an adversarial reinforcement learning framework. In this framework, we use neural reinforcement learning to compute best response policies for both the defender and the adversary to an arbitrary stochastic policy of the other. We then use these in a double-oracle framework to obtain an approximate equilibrium of the game, which in turn yields a robust stochastic policy for the defender. Extensive experiments using case studies in fraud and intrusion detection demonstrate that our approach is effective in creating robust alert prioritization policies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08805](http://arxiv.org/abs/1906.08805)

##### PDF
[http://arxiv.org/pdf/1906.08805](http://arxiv.org/pdf/1906.08805)

