---
layout: post
title: "On Infusing Reachability-Based Safety Assurance within Probabilistic Planning Frameworks for Human-Robot Vehicle Interactions"
date: 2018-12-29 09:04:24
categories: arXiv_RO
tags: arXiv_RO Tracking Prediction
author: Karen Leung, Edward Schmerling, Mo Chen, John Talbot, J. Christian Gerdes, Marco Pavone
mathjax: true
---

* content
{:toc}

##### Abstract
Action anticipation, intent prediction, and proactive behavior are all desirable characteristics for autonomous driving policies in interactive scenarios. Paramount, however, is ensuring safety on the road --- a key challenge in doing so is accounting for uncertainty in human driver actions without unduly impacting planner performance. This paper introduces a minimally-interventional safety controller operating within an autonomous vehicle control stack with the role of ensuring collision-free interaction with an externally controlled (e.g., human-driven) counterpart. We leverage reachability analysis to construct a real-time (100Hz) controller that serves the dual role of (1) tracking an input trajectory from a higher-level planning algorithm using model predictive control, and (2) assuring safety through maintaining the availability of a collision-free escape maneuver as a persistent constraint regardless of whatever future actions the other car takes. A full-scale steer-by-wire platform is used to conduct traffic weaving experiments wherein the two cars, initially side-by-side, must swap lanes in a limited amount of time and distance, emulating cars merging onto/off of a highway. We demonstrate that, with our control stack, the autonomous vehicle is able to avoid collision even when the other car defies the planner's expectations and takes dangerous actions, either carelessly or with the intent to collide, and otherwise deviates minimally from the planned trajectory to the extent required to maintain safety.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11315](http://arxiv.org/abs/1812.11315)

##### PDF
[http://arxiv.org/pdf/1812.11315](http://arxiv.org/pdf/1812.11315)

