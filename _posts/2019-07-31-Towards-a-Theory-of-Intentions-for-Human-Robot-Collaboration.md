---
layout: post
title: "Towards a Theory of Intentions for Human-Robot Collaboration"
date: 2019-07-31 01:31:04
categories: arXiv_AI
tags: arXiv_AI OCR Knowledge
author: Rocio Gomez, Mohan Sridharan, Heather Riley
mathjax: true
---

* content
{:toc}

##### Abstract
The architecture described in this paper encodes a theory of intentions based on the the key principles of non-procrastination, persistence, and automatically limiting reasoning to relevant knowledge and observations. The architecture reasons with transition diagrams of any given domain at two different resolutions, with the fine-resolution description defined as a refinement of, and hence tightly-coupled to, a coarse-resolution description. Non-monotonic logical reasoning with the coarse-resolution description computes an activity (i.e., plan) comprising abstract actions for any given goal. Each abstract action is implemented as a sequence of concrete actions by automatically zooming to and reasoning with the part of the fine-resolution transition diagram relevant to the current coarse-resolution transition and the goal. Each concrete action in this sequence is executed using probabilistic models of the uncertainty in sensing and actuation, and the corresponding fine-resolution outcomes are used to infer coarse-resolution observations that are added to the coarse-resolution history. The architecture's capabilities are evaluated in the context of a simulated robot assisting humans in an office domain, on a physical robot (Baxter) manipulating tabletop objects, and on a wheeled robot (Turtlebot) moving objects to particular places or people. The experimental results indicate improvements in reliability and computational efficiency compared with an architecture that does not include the theory of intentions, and an architecture that does not include zooming for fine-resolution reasoning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13275](http://arxiv.org/abs/1907.13275)

##### PDF
[http://arxiv.org/pdf/1907.13275](http://arxiv.org/pdf/1907.13275)

