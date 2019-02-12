---
layout: post
title: "Learning Best Response Strategies for Agents in Ad Exchanges"
date: 2019-02-10 12:44:13
categories: arXiv_AI
tags: arXiv_AI Quantitative
author: Stavros Gerakaris, Subramanian Ramamoorthy
mathjax: true
---

* content
{:toc}

##### Abstract
Ad exchanges are widely used in platforms for online display advertising. Autonomous agents operating in these exchanges must learn policies for interacting profitably with a diverse, continually changing, but unknown market. We consider this problem from the perspective of a publisher, strategically interacting with an advertiser through a posted price mechanism. The learning problem for this agent is made difficult by the fact that information is censored, i.e., the publisher knows if an impression is sold but no other quantitative information. We address this problem using the Harsanyi-Bellman Ad Hoc Coordination (HBA) algorithm, which conceptualises this interaction in terms of a Stochastic Bayesian Game and arrives at optimal actions by best responding with respect to probabilistic beliefs maintained over a candidate set of opponent behaviour profiles. We adapt and apply HBA to the censored information setting of ad exchanges. Also, addressing the case of stochastic opponents, we devise a strategy based on a Kaplan-Meier estimator for opponent modelling. We evaluate the proposed method using simulations wherein we show that HBA-KM achieves substantially better competitive ratio and lower variance of return than baselines, including a Q-learning agent and a UCB-based online learning agent, and comparable to the offline optimal algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03588](http://arxiv.org/abs/1902.03588)

##### PDF
[http://arxiv.org/pdf/1902.03588](http://arxiv.org/pdf/1902.03588)

