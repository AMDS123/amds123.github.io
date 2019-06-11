---
layout: post
title: "Deterministic Implementations for Reproducibility in Deep Reinforcement Learning"
date: 2019-06-09 12:56:34
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Prabhat Nagarajan, Garrett Warnell, Peter Stone
mathjax: true
---

* content
{:toc}

##### Abstract
While deep reinforcement learning (DRL) has led to numerous successes in recent years, reproducing these successes can be extremely challenging. One reproducibility challenge particularly relevant to DRL is nondeterminism in the training process, which can substantially affect the results. Motivated by this challenge, we study the positive impacts of deterministic implementations in eliminating nondeterminism in training. To do so, we consider the particular case of the deep Q-learning algorithm, for which we produce a deterministic implementation by identifying and controlling all sources of nondeterminism in the training process. One by one, we then allow individual sources of nondeterminism to affect our otherwise deterministic implementation, and measure the impact of each source on the variance in performance. We find that individual sources of nondeterminism can substantially impact the performance of agent, illustrating the benefits of deterministic implementations. In addition, we also discuss the important role of deterministic implementations in achieving exact replicability of results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.05676](http://arxiv.org/abs/1809.05676)

##### PDF
[http://arxiv.org/pdf/1809.05676](http://arxiv.org/pdf/1809.05676)

