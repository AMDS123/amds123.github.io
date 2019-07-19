---
layout: post
title: "PAC-Bayes Control: Learning Policies that Provably Generalize to Novel Environments"
date: 2019-07-17 21:43:11
categories: arXiv_AI
tags: arXiv_AI Optimization Gradient_Descent
author: Anirudha Majumdar, Alec Farid, Anoopkumar Sonar
mathjax: true
---

* content
{:toc}

##### Abstract
Our goal is to learn control policies for robots that provably generalize well to novel environments given a dataset of example environments. The key technical idea behind our approach is to leverage tools from generalization theory in machine learning by exploiting a precise analogy (which we present in the form of a reduction) between generalization of control policies to novel environments and generalization of hypotheses in the supervised learning setting. In particular, we utilize the Probably Approximately Correct (PAC)-Bayes framework, which allows us to obtain upper bounds that hold with high probability on the expected cost of (stochastic) control policies across novel environments. We propose policy learning algorithms that explicitly seek to minimize this upper bound. The corresponding optimization problem can be solved using convex optimization (Relative Entropy Programming in particular) in the setting where we are optimizing over a finite policy space. In the more general setting of continuously parameterized policies (e.g., neural network policies), we minimize this upper bound using stochastic gradient descent. We present simulated results of our approach applied to learning (1) reactive obstacle avoidance policies and (2) neural network-based grasping policies. Our examples demonstrate the potential of our approach to provide strong generalization guarantees for robotic systems with continuous state and action spaces, complicated (e.g., nonlinear) dynamics, rich sensory inputs (e.g., depth images), and neural network-based policies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.04225](http://arxiv.org/abs/1806.04225)

##### PDF
[http://arxiv.org/pdf/1806.04225](http://arxiv.org/pdf/1806.04225)

