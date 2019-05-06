---
layout: post
title: "Technical Report: Cooperative Multi-Target Localization With Noisy Sensors"
date: 2013-02-15 19:52:15
categories: arXiv_CV
tags: arXiv_CV Knowledge Detection
author: Philip Dames, Vijay Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
This technical report is an extended version of the paper 'Cooperative Multi-Target Localization With Noisy Sensors' accepted to the 2013 IEEE International Conference on Robotics and Automation (ICRA). This paper addresses the task of searching for an unknown number of static targets within a known obstacle map using a team of mobile robots equipped with noisy, limited field-of-view sensors. Such sensors may fail to detect a subset of the visible targets or return false positive detections. These measurement sets are used to localize the targets using the Probability Hypothesis Density, or PHD, filter. Robots communicate with each other on a local peer-to-peer basis and with a server or the cloud via access points, exchanging measurements and poses to update their belief about the targets and plan future actions. The server provides a mechanism to collect and synthesize information from all robots and to share the global, albeit time-delayed, belief state to robots near access points. We design a decentralized control scheme that exploits this communication architecture and the PHD representation of the belief state. Specifically, robots move to maximize mutual information between the target set and measurements, both self-collected and those available by accessing the server, balancing local exploration with sharing knowledge across the team. Furthermore, robots coordinate their actions with other robots exploring the same local region of the environment.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1302.3857](https://arxiv.org/abs/1302.3857)

##### PDF
[https://arxiv.org/pdf/1302.3857](https://arxiv.org/pdf/1302.3857)

