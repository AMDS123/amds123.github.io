---
layout: post
title: "Tackling Occlusions & Limited Sensor Range with Set-based Safety Verification"
date: 2019-05-06 12:24:00
categories: arXiv_RO
tags: arXiv_RO Knowledge Face Prediction
author: Piotr Franciszek Orzechowski, Annika Meyer, Martin Lauer
mathjax: true
---

* content
{:toc}

##### Abstract
Provable safety is one of the most critical challenges in automated driving. The behavior of numerous traffic participants in a scene cannot be predicted reliably due to complex interdependencies and the indiscriminate behavior of humans. Additionally, we face high uncertainties and only incomplete environment knowledge. Recent approaches minimize risk with probabilistic and machine learning methods - even under occlusions. These generate comfortable behavior with good traffic flow, but cannot guarantee safety of their maneuvers. 
 Therefore, we contribute a safety verification method for trajectories under occlusions. The field-of-view of the ego vehicle and a map are used to identify critical sensing field edges, each representing a potentially hidden obstacle. The state of occluded obstacles is unknown, but can be over-approximated by intervals over all possible states. 
 Then set-based methods are extended to provide occupancy predictions for obstacles with state intervals. The proposed method can verify the safety of given trajectories (e.g. if they ensure collision-free fail-safe maneuver options) w.r.t. arbitrary safe-state formulations. The potential for provably safe trajectory planning is shown in three evaluative scenarios.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.01262](http://arxiv.org/abs/1807.01262)

##### PDF
[http://arxiv.org/pdf/1807.01262](http://arxiv.org/pdf/1807.01262)

