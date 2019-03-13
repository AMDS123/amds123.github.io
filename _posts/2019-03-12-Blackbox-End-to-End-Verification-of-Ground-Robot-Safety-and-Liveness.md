---
layout: post
title: "Blackbox End-to-End Verification of Ground Robot Safety and Liveness"
date: 2019-03-12 17:38:38
categories: arXiv_RO
tags: arXiv_RO
author: Brandon Bohrer, Yong Kiam Tan, Stefan Mitsch, Andrew Sogokon, Andr&#xe9; Platzer
mathjax: true
---

* content
{:toc}

##### Abstract
We formally prove end-to-end correctness of a ground robot implemented in a simulator. We use an untrusted controller supervised by a verified sandbox. Contributions include: (i) A model of the robot in differential dynamic logic, which specifies assumptions on the controller and robot kinematics, (ii) Formal proofs of safety and liveness for a waypoint-following problem with speed limits, (iii) An automatically synthesized sandbox, which is automatically proven to enforce model compliance at runtime, and (iv) Controllers, planners, and environments for the simulations. 
 The verified sandbox is used to safeguard (unverified) controllers in a realistic simulated environment. Experimental evaluation of the resulting sandboxed implementation confirms safety and high model-compliance, with an inherent trade-off between compliance and performance. The verified sandbox thus serves as a valuable bidirectional link between formal methods and implementation, automating both enforcement of safety and model validation simultaneously.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05073](http://arxiv.org/abs/1903.05073)

##### PDF
[http://arxiv.org/pdf/1903.05073](http://arxiv.org/pdf/1903.05073)

