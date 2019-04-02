---
layout: post
title: "Risk Averse Robust Adversarial Reinforcement Learning"
date: 2019-03-31 23:46:26
categories: arXiv_AI
tags: arXiv_AI Adversarial Reinforcement_Learning Optimization
author: Xinlei Pan, Daniel Seita, Yang Gao, John Canny
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning has recently made significant progress in solving computer games and robotic control tasks. A known problem, though, is that policies overfit to the training environment and may not avoid rare, catastrophic events such as automotive accidents. A classical technique for improving the robustness of reinforcement learning algorithms is to train on a set of randomized environments, but this approach only guards against common situations. Recently, robust adversarial reinforcement learning (RARL) was developed, which allows efficient applications of random and systematic perturbations by a trained adversary. A limitation of RARL is that only the expected control objective is optimized; there is no explicit modeling or optimization of risk. Thus the agents do not consider the probability of catastrophic events (i.e., those inducing abnormally large negative reward), except through their effect on the expected objective. In this paper we introduce risk-averse robust adversarial reinforcement learning (RARARL), using a risk-averse protagonist and a risk-seeking adversary. We test our approach on a self-driving vehicle controller. We use an ensemble of policy networks to model risk as the variance of value functions. We show through experiments that a risk-averse agent is better equipped to handle a risk-seeking adversary, and experiences substantially fewer crashes compared to agents trained without an adversary.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00511](http://arxiv.org/abs/1904.00511)

##### PDF
[http://arxiv.org/pdf/1904.00511](http://arxiv.org/pdf/1904.00511)

