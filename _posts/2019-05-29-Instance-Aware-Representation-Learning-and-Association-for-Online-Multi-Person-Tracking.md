---
layout: post
title: "Instance-Aware Representation Learning and Association for Online Multi-Person Tracking"
date: 2019-05-29 13:16:12
categories: arXiv_CV
tags: arXiv_CV Tracking Represenation_Learning Classification Deep_Learning Detection
author: Hefeng Wu, Yafei Hu, Keze Wang, Hanhui Li, Lin Nie, Hui Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-Person Tracking (MPT) is often addressed within the detection-to-association paradigm. In such approaches, human detections are first extracted in every frame and person trajectories are then recovered by a procedure of data association (usually offline). However, their performances usually degenerate in presence of detection errors, mutual interactions and occlusions. In this paper, we present a deep learning based MPT approach that learns instance-aware representations of tracked persons and robustly online infers states of the tracked persons. Specifically, we design a multi-branch neural network (MBN), which predicts the classification confidences and locations of all targets by taking a batch of candidate regions as input. In our MBN architecture, each branch (instance-subnet) corresponds to an individual to be tracked and new branches can be dynamically created for handling newly appearing persons. Then based on the output of MBN, we construct a joint association matrix that represents meaningful states of tracked persons (e.g., being tracked or disappearing from the scene) and solve it by using the efficient Hungarian algorithm. Moreover, we allow the instance-subnets to be updated during tracking by online mining hard examples, accounting to person appearance variations over time. We comprehensively evaluate our framework on a popular MPT benchmark, demonstrating its excellent performance in comparison with recent online MPT methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12409](http://arxiv.org/abs/1905.12409)

##### PDF
[http://arxiv.org/pdf/1905.12409](http://arxiv.org/pdf/1905.12409)

