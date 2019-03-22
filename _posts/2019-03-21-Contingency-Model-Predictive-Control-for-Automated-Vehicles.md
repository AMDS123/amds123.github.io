---
layout: post
title: "Contingency Model Predictive Control for Automated Vehicles"
date: 2019-03-21 03:12:57
categories: arXiv_RO
tags: arXiv_RO Tracking Prediction
author: John P. Alsterda, Matthew Brown, J. Christian Gerdes
mathjax: true
---

* content
{:toc}

##### Abstract
We present Contingency Model Predictive Control (CMPC), a novel and implementable control framework which tracks a desired path while simultaneously maintaining a contingency plan -- an alternate trajectory to avert an identified potential emergency. In this way, CMPC anticipates events that might take place, instead of reacting when emergencies occur. We accomplish this by adding an additional prediction horizon in parallel to the classical receding MPC horizon. The contingency horizon is constrained to maintain a feasible avoidance solution; as such, CMPC is selectively robust to this emergency while tracking the desired path as closely as possible. After defining the framework mathematically, we demonstrate its effectiveness experimentally by comparing its performance to a state-of-the-art deterministic MPC. The controllers drive an automated research platform through a left-hand turn which may be covered by ice. Contingency MPC prepares for the potential loss of friction by purposefully and intuitively deviating from the prescribed path to approach the turn more conservatively; this deviation significantly mitigates the consequence of encountering ice.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08818](http://arxiv.org/abs/1903.08818)

##### PDF
[http://arxiv.org/pdf/1903.08818](http://arxiv.org/pdf/1903.08818)

