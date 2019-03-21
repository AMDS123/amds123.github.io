---
layout: post
title: "Learning Gentle Object Manipulation with Curiosity-Driven Deep Reinforcement Learning"
date: 2019-03-20 15:07:53
categories: arXiv_RO
tags: arXiv_RO Sparse Reinforcement_Learning
author: Sandy H. Huang, Martina Zambelli, Jackie Kay, Murilo F. Martins, Yuval Tassa, Patrick M. Pilarski, Raia Hadsell
mathjax: true
---

* content
{:toc}

##### Abstract
Robots must know how to be gentle when they need to interact with fragile objects, or when the robot itself is prone to wear and tear. We propose an approach that enables deep reinforcement learning to train policies that are gentle, both during exploration and task execution. In a reward-based learning environment, a natural approach involves augmenting the (task) reward with a penalty for non-gentleness, which can be defined as excessive impact force. However, augmenting with only this penalty impairs learning: policies get stuck in a local optimum which avoids all contact with the environment. Prior research has shown that combining auxiliary tasks or intrinsic rewards can be beneficial for stabilizing and accelerating learning in sparse-reward domains, and indeed we find that introducing a surprise-based intrinsic reward does avoid the no-contact failure case. However, we show that a simple dynamics-based surprise is not as effective as penalty-based surprise. Penalty-based surprise, based on predicting forceful contacts, has a further benefit: it encourages exploration which is contact-rich yet gentle. We demonstrate the effectiveness of the approach using a complex, tendon-powered robot hand with tactile sensors. Videos are available at <a href="http://sites.google.com/view/gentlemanipulation.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08542](http://arxiv.org/abs/1903.08542)

##### PDF
[http://arxiv.org/pdf/1903.08542](http://arxiv.org/pdf/1903.08542)

