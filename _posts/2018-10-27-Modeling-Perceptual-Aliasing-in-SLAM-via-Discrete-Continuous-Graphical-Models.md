---
layout: post
title: "Modeling Perceptual Aliasing in SLAM via Discrete-Continuous Graphical Models"
date: 2018-10-27 19:03:35
categories: arXiv_RO
tags: arXiv_RO Optimization Inference SLAM Relation
author: Pierre-Yves Lajoie, Siyi Hu, Giovanni Beltrame, Luca Carlone
mathjax: true
---

* content
{:toc}

##### Abstract
Perceptual aliasing is one of the main causes of failure for Simultaneous Localization and Mapping (SLAM) systems operating in the wild. Perceptual aliasing is the phenomenon where different places generate a similar visual (or, in general, perceptual) footprint. This causes spurious measurements to be fed to the SLAM estimator, which typically results in incorrect localization and mapping results. The problem is exacerbated by the fact that those outliers are highly correlated, in the sense that perceptual aliasing creates a large number of mutually- consistent outliers. Another issue stems from the fact that state-of-the-art techniques typically rely on a given trajectory guess (e.g., from odometry) to discern between inliers and outliers and this makes the resulting pipeline brittle, since the accumulation of error may result in incorrect choices and recovery from failures is far from trivial. This work provides a unified framework to model perceptual aliasing in SLAM and provides practical algorithms that can cope with outliers without relying on any initial guess. We present two main contributions. The first is a Discrete-Continuous Graphical Model (DC-GM) for SLAM: the continuous portion of the DC-GM captures the standard SLAM problem, while the discrete portion describes the selection of the outliers and models their correlation. The second contribution is a semidefinite relaxation to perform inference in the DC-GM that returns estimates with provable sub-optimality guarantees. Experimental results on standard benchmarking datasets show that the proposed technique compares favorably with state-of-the-art methods while not requiring parameter tuning and not relying on an initial guess for optimization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11692](http://arxiv.org/abs/1810.11692)

##### PDF
[http://arxiv.org/pdf/1810.11692](http://arxiv.org/pdf/1810.11692)

