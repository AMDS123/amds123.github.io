---
layout: post
title: "Deep Reinforcement Learning for Event-Driven Multi-Agent Decision Processes"
date: 2019-05-29 17:15:10
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Kunal Menda, Yi-Chun Chen, Justin Grana, James W. Bono, Brendan D. Tracey, Mykel J. Kochenderfer, David Wolpert
mathjax: true
---

* content
{:toc}

##### Abstract
The incorporation of macro-actions (temporally extended actions) into multi-agent decision problems has the potential to address the curse of dimensionality associated with such decision problems. Since macro-actions last for stochastic durations, multiple agents executing decentralized policies in cooperative environments must act asynchronously. We present an algorithm that modifies generalized advantage estimation for temporally extended actions, allowing a state-of-the-art policy optimization algorithm to optimize policies in Dec-POMDPs in which agents act asynchronously. We show that our algorithm is capable of learning optimal policies in two cooperative domains, one involving real-time bus holding control and one involving wildfire fighting with unmanned aircraft. Our algorithm works by framing problems as "event-driven decision processes," which are scenarios in which the sequence and timing of actions and events are random and governed by an underlying stochastic process. In addition to optimizing policies with continuous state and action spaces, our algorithm also facilitates the use of event-driven simulators, which do not require time to be discretized into time-steps. We demonstrate the benefit of using event-driven simulation in the context of multiple agents taking asynchronous actions. We show that fixed time-step simulation risks obfuscating the sequence in which closely separated events occur, adversely affecting the policies learned. In addition, we show that arbitrarily shrinking the time-step scales poorly with the number of agents.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.06656](http://arxiv.org/abs/1709.06656)

##### PDF
[http://arxiv.org/pdf/1709.06656](http://arxiv.org/pdf/1709.06656)

