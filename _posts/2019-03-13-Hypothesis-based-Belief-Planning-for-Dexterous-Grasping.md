---
layout: post
title: "Hypothesis-based Belief Planning for Dexterous Grasping"
date: 2019-03-13 14:46:28
categories: arXiv_AI
tags: arXiv_AI
author: Claudio Zito, Valerio Ortenzi, Maxime Adjigble, Marek Kopicki, Rustam Stolkin, Jeremy L. Wyatt
mathjax: true
---

* content
{:toc}

##### Abstract
Belief space planning is a viable alternative to formalise partially observable control problems and, in the recent years, its application to robot manipulation problems has grown. However, this planning approach was tried successfully only on simplified control problems. In this paper, we apply belief space planning to the problem of planning dexterous reach-to-grasp trajectories under object pose uncertainty. In our framework, the robot perceives the object to be grasped on-the-fly as a point cloud and compute a full 6D, non-Gaussian distribution over the object's pose (our belief space). The system has no limitations on the geometry of the object, i.e., non-convex objects can be represented, nor assumes that the point cloud is a complete representation of the object. A plan in the belief space is then created to reach and grasp the object, such that the information value of expected contacts along the trajectory is maximised to compensate for the pose uncertainty. If an unexpected contact occurs when performing the action, such information is used to refine the pose distribution and triggers a re-planning. Experimental results show that our planner (IR3ne) improves grasp reliability and compensates for the pose uncertainty such that it doubles the proportion of grasps that succeed on a first attempt.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05517](http://arxiv.org/abs/1903.05517)

##### PDF
[http://arxiv.org/pdf/1903.05517](http://arxiv.org/pdf/1903.05517)

