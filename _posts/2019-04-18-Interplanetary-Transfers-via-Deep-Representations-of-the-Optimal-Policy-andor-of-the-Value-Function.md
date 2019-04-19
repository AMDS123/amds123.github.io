---
layout: post
title: "Interplanetary Transfers via Deep Representations of the Optimal Policy and/or of the Value Function"
date: 2019-04-18 14:33:34
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Dario Izzo, Ekin &#xd6;zt&#xfc;rk, Marcus M&#xe4;rtens
mathjax: true
---

* content
{:toc}

##### Abstract
A number of applications to interplanetary trajectories have been recently proposed based on deep networks. These approaches often rely on the availability of a large number of optimal trajectories to learn from. In this paper we introduce a new method to quickly create millions of optimal spacecraft trajectories from a single nominal trajectory. Apart from the generation of the nominal trajectory, no additional optimal control problems need to be solved as all the trajectories, by construction, satisfy Pontryagin's minimum principle and the relevant transversality conditions. We then consider deep feed forward neural networks and benchmark three learning methods on the created dataset: policy imitation, value function learning and value function gradient learning. Our results are shown for the case of the interplanetary trajectory optimization problem of reaching Venus orbit, with the nominal trajectory starting from the Earth. We find that both policy imitation and value function gradient learning are able to learn the optimal state feedback, while in the case of value function learning the optimal policy is not captured, only the final value of the optimal propellant mass is.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08809](http://arxiv.org/abs/1904.08809)

##### PDF
[http://arxiv.org/pdf/1904.08809](http://arxiv.org/pdf/1904.08809)

