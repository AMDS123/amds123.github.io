---
layout: post
title: "Truly Proximal Policy Optimization"
date: 2019-03-19 11:18:29
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Yuhui Wang, Hao He, Xiaoyang Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Proximal policy optimization (PPO) is one of the most successful deep reinforcement learning methods, achieving state-of-the-art performance across a wide range of challenging tasks. However, its optimization behavior is still far from being fully understood. In this paper, we show that PPO could neither strictly restrict the probability ratio as it devotes nor enforce a well-defined trust region constraint, which means that it may still suffer from the risk of performance instability. To address this issue, we present an enhanced PPO method, named Trust Region-based PPO with Rollback (TR-PPO-RB). Two critical improvements are made in our method: 1) it adopts a new clipping function to support a rollback behavior to restrict the ratio between the new policy and the old one; 2) the triggering condition for clipping is replaced with a trust region-based one, which is theoretically justified according to the trust region theorem. It seems, by adhering more truly to the "proximal" property - restricting the policy within the trust region, the new algorithm improves the original PPO on both stability and sample efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07940](http://arxiv.org/abs/1903.07940)

##### PDF
[http://arxiv.org/pdf/1903.07940](http://arxiv.org/pdf/1903.07940)

