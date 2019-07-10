---
layout: post
title: "Estimating Mass Distribution of Articulated Objects through Physical Interaction"
date: 2019-07-09 03:32:05
categories: arXiv_AI
tags: arXiv_AI Face Reinforcement_Learning
author: Niranjan Kumar Kannabiran, Irfan Essa, C. Karen Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the problem of estimating the mass distribution of an articulated object by an interactive agent. Our method predicts the mass distribution accurately only using information that can be reliably acquired by the limited sensing and actuating capabilities of a robotic agent that interacts with it. Inspired by the role of exploratory play in human infants, we take the combined approach of supervised and reinforcement learning to train the agent such that it learns to strategically interact with the object for estimating its mass distribution. Our method consists of two neural networks: the policy network which decides how to interact with the object, and the predictor network that estimates the mass distribution given a history of observations and interactions. Using our method, we train a robotic arm to estimate the mass distribution of an object with moving parts (e.g. an articulated rigid body system) by pushing it on a surface with unknown friction properties. We also test the robustness of our learned model by transferring it to another robot arm with different end-effector geometry. The empirical results show that our method significantly outperforms the baseline agent which uses random pushes to collect data for estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03964](http://arxiv.org/abs/1907.03964)

##### PDF
[http://arxiv.org/pdf/1907.03964](http://arxiv.org/pdf/1907.03964)

