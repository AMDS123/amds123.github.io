---
layout: post
title: "Adaptive Prior Selection for Repertoire-based Online Learning in Robotics"
date: 2019-07-16 14:26:13
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Rituraj Kaushik, Pierre Desreumaux, Jean-Baptiste Mouret
mathjax: true
---

* content
{:toc}

##### Abstract
Among the data-efficient approaches for online adaptation in robotics (meta-learning, model-based reinforcement learning, etc.), repertoire-based learning (1) generates a large and diverse set policies in simulation that acts as a "reservoir" for future adaptations and (2) learns to pick online the best working policies according to the current situation (e.g., a damaged robot, a new object, etc.). Each of these policies performs a different task, for instance, walking in different directions; these policies are then sequenced with a planning algorithm to achieve the given task. In this paper, we relax the assumption of previous works that a single repertoire is enough for adaptation. Instead, we generate repertoires for many different situations (e.g., with a missing leg, on different floors, etc.) in simulation that act as priors for adaptation. Our main contribution is an algorithm, APROL (Adaptive Prior selection for Repertoire-based Online Learning) to plan the next action by incorporating these priors when the robot has no information about the current situation. We evaluate APROL on two simulated tasks: (1) pushing unknown objects of various shapes and sizes with a kuka arm and (2) a goal reaching task with a damaged hexapod robot. We compare with "Reset-free Trial and Error" (RTE) and various single repertoire-based baselines. The results show that APROL solves both tasks in less interaction time than the baselines. Additionally, we demonstrate APROL on a real, damaged hexapod that quickly learns compensatory policies to reach a goal by avoiding obstacle in the path.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07029](http://arxiv.org/abs/1907.07029)

##### PDF
[http://arxiv.org/pdf/1907.07029](http://arxiv.org/pdf/1907.07029)

