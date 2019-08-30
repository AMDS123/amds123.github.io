---
layout: post
title: "A Belief Propagation Algorithm for Multipath-Based SLAM"
date: 2019-08-29 12:49:20
categories: arXiv_RO
tags: arXiv_RO Face SLAM
author: Erik Leitinger, Florian Meyer, Franz Hlawatsch, Klaus Witrisal, Fredrik Tufvesson, Moe Z. Win
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simultaneous localization and mapping (SLAM) algorithm that is based on radio signals and the association of specular multipath components (MPCs) with geometric features. Especially in indoor scenarios, robust localization from radio signals is challenging due to diffuse multipath propagation, unknown MPC-feature association, and limited visibility of features. In our approach, specular reflections at flat surfaces are described in terms of virtual anchors (VAs) that are mirror images of the physical anchors (PAs). The positions of these VAs and possibly also of the PAs are unknown. We develop a Bayesian model of the SLAM problem and represent it by a factor graph, which enables the use of belief propagation (BP) for efficient marginalization of the joint posterior distribution. The resulting BP-based SLAM algorithm detects the VAs associated with the PAs and estimates jointly the time-varying position of the mobile agent and the positions of the VAs and possibly also of the PAs, thereby leveraging the MPCs in the radio signal for improved accuracy and robustness of agent localization. The algorithm has a low computational complexity and scales well in all relevant system parameters. Experimental results using both synthetic measurements and real ultra-wideband radio signals demonstrate the excellent performance of the algorithm in challenging indoor environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.04463](http://arxiv.org/abs/1801.04463)

##### PDF
[http://arxiv.org/pdf/1801.04463](http://arxiv.org/pdf/1801.04463)

