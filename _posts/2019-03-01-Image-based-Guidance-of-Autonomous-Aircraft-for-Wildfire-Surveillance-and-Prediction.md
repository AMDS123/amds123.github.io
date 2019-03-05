---
layout: post
title: "Image-based Guidance of Autonomous Aircraft for Wildfire Surveillance and Prediction"
date: 2019-03-01 21:47:49
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Survey Prediction
author: Kyle D. Julian, Mykel J. Kochenderfer
mathjax: true
---

* content
{:toc}

##### Abstract
Small unmanned aircraft can help firefighters combat wildfires by providing real-time surveillance of the growing fires. However, guiding the aircraft autonomously given only wildfire images is a challenging problem. This work models noisy images obtained from on-board cameras and proposes two approaches to filtering the wildfire images. The first approach uses a simple Kalman filter to reduce noise and update a belief map in observed areas. The second approach uses a particle filter to predict wildfire growth and uses observations to estimate uncertainties relating to wildfire expansion. The belief maps are used to train a deep reinforcement learning controller, which learns a policy to navigate the aircraft to survey the wildfire while avoiding flight directly over the fire. Simulation results show that the proposed controllers precisely guide the aircraft and accurately estimate wildfire growth, and a study of observation noise demonstrates the robustness of the particle filter approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.02455](http://arxiv.org/abs/1810.02455)

##### PDF
[http://arxiv.org/pdf/1810.02455](http://arxiv.org/pdf/1810.02455)

