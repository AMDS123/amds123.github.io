---
layout: post
title: "Composable Action-Conditioned Predictors: Flexible Off-Policy Learning for Robot Navigation"
date: 2018-10-16 17:49:43
categories: arXiv_AI
tags: arXiv_AI Object_Detection Reinforcement_Learning Detection
author: Gregory Kahn, Adam Villaflor, Pieter Abbeel, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
A general-purpose intelligent robot must be able to learn autonomously and be able to accomplish multiple tasks in order to be deployed in the real world. However, standard reinforcement learning approaches learn separate task-specific policies and assume the reward function for each task is known a priori. We propose a framework that learns event cues from off-policy data, and can flexibly combine these event cues at test time to accomplish different tasks. These event cue labels are not assumed to be known a priori, but are instead labeled using learned models, such as computer vision detectors, and then `backed up' in time using an action-conditioned predictive model. We show that a simulated robotic car and a real-world RC car can gather data and train fully autonomously without any human-provided labels beyond those needed to train the detectors, and then at test-time be able to accomplish a variety of different tasks. Videos of the experiments and code can be found at https://github.com/gkahn13/CAPs

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07167](http://arxiv.org/abs/1810.07167)

##### PDF
[http://arxiv.org/pdf/1810.07167](http://arxiv.org/pdf/1810.07167)

