---
layout: post
title: "Learning Task Constraints from Demonstration for Hybrid Force/Position Control"
date: 2019-06-29 20:30:11
categories: arXiv_RO
tags: arXiv_RO Face Tracking
author: Adam Conkey, Tucker Hermans
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel method for learning hybrid force/position control from demonstration. We learn a dynamic constraint frame aligned to the direction of desired force using Cartesian Dynamic Movement Primitives. In contrast to approaches that utilize a fixed constraint frame, our approach easily accommodates tasks with rapidly changing task constraints over time. We activate only one degree of freedom for force control at any given time, ensuring motion is always possible orthogonal to the direction of desired force. Since we utilize demonstrated forces to learn the constraint frame, we are able to compensate for forces not detected by methods that learn only from the demonstrated kinematic motion, such as frictional forces between the end-effector and the contact surface. We additionally propose novel extensions to the Dynamic Movement Primitive (DMP) framework that encourage robust transition from free-space motion to in-contact motion in spite of environment uncertainty. We incorporate force feedback and a dynamically shifting goal to reduce forces applied to the environment and retain stable contact while enabling force control. Our methods exhibit low impact forces on contact and low steady-state tracking error.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03026](http://arxiv.org/abs/1811.03026)

##### PDF
[http://arxiv.org/pdf/1811.03026](http://arxiv.org/pdf/1811.03026)

