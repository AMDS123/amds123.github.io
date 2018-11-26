---
layout: post
title: "Continuous-Time Gaussian Process Motion Planning via Probabilistic Inference"
date: 2018-11-22 05:40:37
categories: arXiv_RO
tags: arXiv_RO Sparse Optimization Inference
author: Mustafa Mukadam, Jing Dong, Xinyan Yan, Frank Dellaert, Byron Boots
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel formulation of motion planning, for continuous-time trajectories, as probabilistic inference. We first show how smooth continuous-time trajectories can be represented by a small number of states using sparse Gaussian process (GP) models. We next develop an efficient gradient-based optimization algorithm that exploits this sparsity and GP interpolation. We call this algorithm the Gaussian Process Motion Planner (GPMP). We then detail how motion planning problems can be formulated as probabilistic inference on a factor graph. This forms the basis for GPMP2, a very efficient algorithm that combines GP representations of trajectories with fast, structure-exploiting inference via numerical optimization. Finally, we extend GPMP2 to an incremental algorithm, iGPMP2, that can efficiently replan when conditions change. We benchmark our algorithms against several sampling-based and trajectory optimization-based motion planning algorithms on planning problems in multiple environments. Our evaluation reveals that GPMP2 is several times faster than previous algorithms while retaining robustness. We also benchmark iGPMP2 on replanning problems, and show that it can find successful solutions in a fraction of the time required by GPMP2 to replan from scratch.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1707.07383](http://arxiv.org/abs/1707.07383)

##### PDF
[http://arxiv.org/pdf/1707.07383](http://arxiv.org/pdf/1707.07383)

