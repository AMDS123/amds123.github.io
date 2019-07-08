---
layout: post
title: "Longitudinal Dynamic versus Kinematic Models for Car-Following Control Using Deep Reinforcement Learning"
date: 2019-07-05 14:29:09
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Yuan Lin, John McPhee, Nasser L. Azad
mathjax: true
---

* content
{:toc}

##### Abstract
The majority of current studies on autonomous vehicle control via deep reinforcement learning (DRL) utilize point-mass kinematic models, neglecting vehicle dynamics which includes acceleration delay and acceleration command dynamics. The acceleration delay, which results from sensing and actuation delays, results in delayed execution of the control inputs. The acceleration command dynamics dictates that the actual vehicle acceleration does not rise up to the desired command acceleration instantaneously due to dynamics. In this work, we investigate the feasibility of applying DRL controllers trained using vehicle kinematic models to more realistic driving control with vehicle dynamics. We consider a particular longitudinal car-following control, i.e., Adaptive Cruise Control (ACC), problem solved via DRL using a point-mass kinematic model. When such a controller is applied to car following with vehicle dynamics, we observe significantly degraded car-following performance. Therefore, we redesign the DRL framework to accommodate the acceleration delay and acceleration command dynamics by adding the delayed control inputs and the actual vehicle acceleration to the reinforcement learning environment state, respectively. The training results show that the redesigned DRL controller results in near-optimal control performance of car following with vehicle dynamics considered when compared with dynamic programming solutions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08314](http://arxiv.org/abs/1905.08314)

##### PDF
[http://arxiv.org/pdf/1905.08314](http://arxiv.org/pdf/1905.08314)

