---
layout: post
title: "Incremental Scene Synthesis"
date: 2018-11-29 16:41:44
categories: arXiv_CV
tags: arXiv_CV SLAM
author: Benjamin Planche, Xuejian Rong, Ziyan Wu, Srikrishna Karanam, Harald Kosch, YingLi Tian, Andreas Hutter, Jan Ernst
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to incrementally generate complete 2D or 3D scenes with the following properties: (a) it is globally consistent at each step according to a learned scene prior, (b) real observations of an actual scene can be incorporated while observing global consistency, (c) unobserved parts of the scene can be hallucinated locally in consistence with previous observations, hallucinations and global priors, and (d) the hallucinations are statistical in nature, i.e., different consistent scenes can be generated from the same observations. To achieve this, we model the motion of an active agent through a virtual scene, where the agent at each step can either perceive a true (i.e. observed) part of the scene or generate a local hallucination. The latter can be interpreted as the expectation of the agent at this step through the scene and can already be useful, e.g., in autonomous navigation. In the limit of observing real data at each point, our method converges to solving the SLAM problem. In the limit of never observing real data, it samples entirely imagined scenes from the prior distribution. Besides autonomous agents, applications include problems where large data is required for training and testing robust real-world applications, but few data is available, necessitating data generation. We demonstrate efficacy on various 2D as well as preliminary 3D data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12297](http://arxiv.org/abs/1811.12297)

##### PDF
[http://arxiv.org/pdf/1811.12297](http://arxiv.org/pdf/1811.12297)

