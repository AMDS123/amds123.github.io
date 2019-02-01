---
layout: post
title: "Comparing Task Simplifications to Learn Closed-Loop Object Picking Using Deep Reinforcement Learning"
date: 2019-01-31 18:03:12
categories: arXiv_RO
tags: arXiv_RO Sparse Reinforcement_Learning
author: Michel Breyer, Fadri Furrer, Tonci Novkovic, Roland Siegwart, Juan Nieto
mathjax: true
---

* content
{:toc}

##### Abstract
Enabling autonomous robots to interact in unstructured environments with dynamic objects requires manipulation capabilities that can deal with clutter, changes, and objects' variability. This paper presents a comparison of different reinforcement learning-based approaches for object picking with a robotic manipulator. We learn closed-loop policies mapping depth camera inputs to motion commands and compare different approaches to keep the problem tractable, including reward shaping, curriculum learning and using a policy pre-trained on a task with a reduced action set to warm-start the full problem. For efficient and more flexible data collection, we train in simulation and transfer the policies to a real robot. We show that using curriculum learning, policies learned with a sparse reward formulation can be trained at similar rates as with a shaped reward. These policies result in success rates comparable to the policy initialized on the simplified task. We could successfully transfer these policies to the real robot with only minor modifications of the depth image filtering. We found that using a heuristic to warm-start the training was useful to enforce desired behavior, while the policies trained from scratch using a curriculum learned better to cope with unseen scenarios where objects are removed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.04996](http://arxiv.org/abs/1803.04996)

##### PDF
[http://arxiv.org/pdf/1803.04996](http://arxiv.org/pdf/1803.04996)

