---
layout: post
title: "Learning Extreme Hummingbird Maneuvers on Flapping Wing Robots"
date: 2019-02-25 21:27:57
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Fan Fei, Zhan Tu, Jian Zhang, Xinyan Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Biological studies show that hummingbirds can perform extreme aerobatic maneuvers during fast escape. Given a sudden looming visual stimulus at hover, a hummingbird initiates a fast backward translation coupled with a 180-degree yaw turn, which is followed by instant posture stabilization in just under 10 wingbeats. Consider the wingbeat frequency of 40Hz, this aggressive maneuver is carried out in just 0.2 seconds. Inspired by the hummingbirds' near-maximal performance during such extreme maneuvers, we developed a flight control strategy and experimentally demonstrated that such maneuverability can be achieved by an at-scale 12-gram hummingbird robot equipped with just two actuators. The proposed hybrid control policy combines model-based nonlinear control with model-free reinforcement learning. We use model-based nonlinear control for nominal flight control, as the dynamic model is relatively accurate for these conditions. However, during extreme maneuver, the modeling error becomes unmanageable. A model-free reinforcement learning policy trained in simulation was optimized to 'destabilize' the system and maximize the performance during maneuvering. The hybrid policy manifests a maneuver that is close to that observed in hummingbirds. Direct simulation-to-real transfer is achieved, demonstrating the hummingbird-like fast evasive maneuvers on the at-scale hummingbird robot.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09626](http://arxiv.org/abs/1902.09626)

##### PDF
[http://arxiv.org/pdf/1902.09626](http://arxiv.org/pdf/1902.09626)

