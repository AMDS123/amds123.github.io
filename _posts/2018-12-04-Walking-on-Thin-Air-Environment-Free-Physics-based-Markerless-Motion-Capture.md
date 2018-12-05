---
layout: post
title: "Walking on Thin Air: Environment-Free Physics-based Markerless Motion Capture"
date: 2018-12-04 03:47:13
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Tracking Optimization Prediction Quantitative
author: Micha Livne, Leonid Sigal, Marcus A. Brubaker, David J. Fleet
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a generative approach to physics-based motion capture. Unlike prior attempts to incorporate physics into tracking that assume the subject and scene geometry are calibrated and known a priori, our approach is automatic and online. This distinction is important since calibration of the environment is often difficult, especially for motions with props, uneven surfaces, or outdoor scenes. The use of physics in this context provides a natural framework to reason about contact and the plausibility of recovered motions. We propose a fast data-driven parametric body model, based on linear-blend skinning, which decouples deformations due to pose, anthropometrics and body shape. Pose (and shape) parameters are estimated using robust ICP optimization with physics-based dynamic priors that incorporate contact. Contact is estimated from torque trajectories and predictions of which contact points were active. To our knowledge, this is the first approach to take physics into account without explicit {\em a priori} knowledge of the environment or body dimensions. We demonstrate effective tracking from a noisy single depth camera, improving on state-of-the-art results quantitatively and producing better qualitative results, reducing visual artifacts like foot-skate and jitter.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01203](http://arxiv.org/abs/1812.01203)

##### PDF
[http://arxiv.org/pdf/1812.01203](http://arxiv.org/pdf/1812.01203)

