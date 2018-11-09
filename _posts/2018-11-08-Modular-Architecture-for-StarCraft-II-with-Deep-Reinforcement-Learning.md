---
layout: post
title: "Modular Architecture for StarCraft II with Deep Reinforcement Learning"
date: 2018-11-08 17:13:50
categories: arXiv_AI
tags: arXiv_AI Review Reinforcement_Learning
author: Dennis Lee, Haoran Tang, Jeffrey O Zhang, Huazhe Xu, Trevor Darrell, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel modular architecture for StarCraft II AI. The architecture splits responsibilities between multiple modules that each control one aspect of the game, such as build-order selection or tactics. A centralized scheduler reviews macros suggested by all modules and decides their order of execution. An updater keeps track of environment changes and instantiates macros into series of executable actions. Modules in this framework can be optimized independently or jointly via human design, planning, or reinforcement learning. We apply deep reinforcement learning techniques to training two out of six modules of a modular agent with self-play, achieving 94% or 87% win rates against the "Harder" (level 5) built-in Blizzard bot in Zerg vs. Zerg matches, with or without fog-of-war.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.03555](https://arxiv.org/abs/1811.03555)

##### PDF
[https://arxiv.org/pdf/1811.03555](https://arxiv.org/pdf/1811.03555)

