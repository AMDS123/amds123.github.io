---
layout: post
title: "Online UAV Path Planning for Joint Detection and Tracking of Multiple Radio-tagged Objects"
date: 2018-08-09 00:18:23
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Hoa Van Nguyen, S. Hamid Rezatofighi, Ba-Ngu Vo, Damith C. Ranasinghe
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of online path planning for joint detection and tracking of multiple unknown radio-tagged objects. This is a necessary task for gathering spatio-temporal information using UAVs with on-board sensors in a range of monitoring applications. In this paper, we propose an online path planning algorithm with joint detection and tracking for the problem because signal measurements from these object are inherently noisy. We derive a partially observable Markov decision process with a random finite set track-before-detect (TBD) multi-object filter. We show that, in practice, the likelihood function of raw signals received by the UAV transformed into the time-frequency domain is separable for multiple radio-tagged objects and results in a numerically efficient multi-object TBD filter. We derive a TBD filter with a jump Markov system to accommodate maneuvering objects capable of switching between different dynamic modes. Further, we impose a practical constraint using a void probability formulation to maintain a safe distance between the UAV and objects of interest. Our evaluations demonstrate the capability of our approach handle multiple radio-tagged object behaviors such as birth, death, motion modes and the superiority of the proposed online planning method with the TBD-based filter at tracking and detecting objects compared to the detection-based counterpart, especially under low signal-to-noise ratio environments.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.04445](https://arxiv.org/abs/1808.04445)

##### PDF
[https://arxiv.org/pdf/1808.04445](https://arxiv.org/pdf/1808.04445)

