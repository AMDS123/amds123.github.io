---
layout: post
title: "Learning Particle Dynamics for Manipulating Rigid Bodies, Deformable Objects, and Fluids"
date: 2019-04-18 00:37:03
categories: arXiv_AI
tags: arXiv_AI
author: Yunzhu Li, Jiajun Wu, Russ Tedrake, Joshua B. Tenenbaum, Antonio Torralba
mathjax: true
---

* content
{:toc}

##### Abstract
Real-life control tasks involve matters of various substances---rigid or soft bodies, liquid, gas---each with distinct physical behaviors. This poses challenges to traditional rigid-body physics engines. Particle-based simulators have been developed to model the dynamics of these complex scenes; however, relying on approximation techniques, their simulation often deviates from real-world physics, especially in the long term. In this paper, we propose to learn a particle-based simulator for complex control tasks. Combining learning with particle-based systems brings in two major benefits: first, the learned simulator, just like other particle-based systems, acts widely on objects of different materials; second, the particle-based representation poses strong inductive bias for learning: particles of the same type have the same dynamics within. This enables the model to quickly adapt to new environments of unknown dynamics within a few observations. We demonstrate robots achieving complex manipulation tasks using the learned simulator, such as manipulating fluids and deformable foam, with experiments both in simulation and in the real world. Our study helps lay the foundation for robot learning of dynamic scenes with particle-based representations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.01566](http://arxiv.org/abs/1810.01566)

##### PDF
[http://arxiv.org/pdf/1810.01566](http://arxiv.org/pdf/1810.01566)

