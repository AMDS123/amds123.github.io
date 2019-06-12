---
layout: post
title: "Accurate Energetic Constraints for Passive Grasp Stability Analysis"
date: 2019-06-10 22:04:58
categories: arXiv_RO
tags: arXiv_RO
author: Maximilian Haas-Heger, Matei Ciocarlie
mathjax: true
---

* content
{:toc}

##### Abstract
Passive reaction effects in grasp stability analysis occur when the contact forces and joint torques applied by a grasp change in response to external disturbances applied to the grasped object. For example, nonbackdrivable actuators (e.g. highly geared servos) will passively resist external disturbances without an actively applied command; for numerous robot hands using such motors, these effects can be highly beneficial as they increase grasp resistance without requiring active control. We introduce a grasp stability analysis method that can model these effects, and, for a given grasp, distinguish between disturbances that will be passively resisted and those that will not. We find that, in order to achieve this, the grasp model must include accurate energetic constraints. One way to achieve this is to consider the Maximum Dissipation Principle (MDP), a part of the Coulomb friction model that is rarely used in grasp stability analysis. However, the MDP constraints are non-convex, and difficult to solve efficiently. We thus introduce a convex relaxation method, along with an algorithm that successively refines this relaxation locally in order to obtain solutions to arbitrary accuracy efficiently. Our resulting algorithm can determine if a grasp is passively stable, solve for equilibrium contact forces and compute optimal actuator commands for stability. Its implementation is publicly available as part of the open-source GraspIt! simulator.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00134](http://arxiv.org/abs/1905.00134)

##### PDF
[http://arxiv.org/pdf/1905.00134](http://arxiv.org/pdf/1905.00134)

