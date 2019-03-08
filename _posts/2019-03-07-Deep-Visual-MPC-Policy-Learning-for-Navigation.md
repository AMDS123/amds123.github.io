---
layout: post
title: "Deep Visual MPC-Policy Learning for Navigation"
date: 2019-03-07 06:54:37
categories: arXiv_RO
tags: arXiv_RO
author: Noriaki Hirose, Fei Xia, Roberto Martin-Martin, Amir Sadeghian, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
Humans can routinely follow a trajectory defined by a list of images/landmarks. However, traditional robot navigation methods require accurate mapping of the environment, localization, and planning. Moreover, these methods are sensitive to subtle changes in the environment. In this paper, we propose a Deep Visual MPC-policy learning method that can perform visual navigation while avoiding collisions with unseen objects on the navigation path. Our model PoliNet takes in as input a visual trajectory and the image of the robot's current view and outputs velocity commands for a planning horizon of $N$ steps that optimally balance between trajectory following and obstacle avoidance. PoliNet is trained using a strong image predictive model and traversability estimation model in a MPC setup, with minimal human supervision. Different from prior work, PoliNet can be applied to new scenes without retraining. We show experimentally that the robot can follow a visual trajectory when varying start position and in the presence of previously unseen obstacles. We validated our algorithm with tests both in a realistic simulation environment and in the real world. We also show that we can generate visual trajectories in simulation and execute the corresponding path in the real environment. Our approach outperforms classical approaches as well as previous learning-based baselines in success rate of goal reaching, sub-goal coverage rate, and computational load.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02749](http://arxiv.org/abs/1903.02749)

##### PDF
[http://arxiv.org/pdf/1903.02749](http://arxiv.org/pdf/1903.02749)

