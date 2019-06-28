---
layout: post
title: "Automatic Detection of Myocontrol Failures Based upon Situational Context Information"
date: 2019-06-27 11:46:15
categories: arXiv_RO
tags: arXiv_RO Prediction Detection
author: Karoline Heiwolt, Claudio Zito, Markus Nowak, Claudio Castellini, Rustam Stolkin
mathjax: true
---

* content
{:toc}

##### Abstract
Myoelectric control systems for assistive devices are still unreliable. The user's input signals can become unstable over time due to e.g. fatigue, electrode displacement, or sweat. Hence, such controllers need to be constantly updated and heavily rely on user feedback. In this paper, we present an automatic failure detection method which learns when plausible predictions become unreliable and model updates are necessary. Our key insight is to enhance the control system with a set of generative models that learn sensible behaviour for a desired task from human demonstration. We illustrate our approach on a grasping scenario in Virtual Reality, in which the user is asked to grasp a bottle on a table. From demonstration our model learns the reach-to-grasp motion from a resting position to two grasps (power grasp and tridigital grasp) and how to predict the most adequate grasp from local context, e.g. tridigital grasp on the bottle cap or around the bottleneck. By measuring the error between new grasp attempts and the model prediction, the system can effectively detect which input commands do not reflect the user's intention. We evaluated our model in two cases: i) with both position and rotation information of the wrist pose, and ii) with only rotational information. Our results show that our approach detects statistically highly significant differences in error distributions with p &lt; 0.001 between successful and failed grasp attempts in both cases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11564](http://arxiv.org/abs/1906.11564)

##### PDF
[http://arxiv.org/pdf/1906.11564](http://arxiv.org/pdf/1906.11564)

