---
layout: post
title: "Incremental Scene Synthesis"
date: 2019-05-29 20:41:46
categories: arXiv_CV
tags: arXiv_CV SLAM
author: Benjamin Planche, Xuejian Rong, Ziyan Wu, Srikrishna Karanam, Harald Kosch, YingLi Tian, Jan Ernst, Andreas Hutter
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to incrementally generate complete 2D or 3D scenes with the following properties: (a) it is globally consistent at each step according to a learned scene prior, (b) real observations of a scene can be incorporated while observing global consistency, (c) unobserved regions can be hallucinated locally in consistence with previous observations, hallucinations and global priors, and (d) hallucinations are statistical in nature, i.e., different scenes can be generated from the same observations. To achieve this, we model the virtual scene, where the active agent at each step can either perceive an observed part of the scene or generate a local hallucination. The latter can be interpreted as the agent's expectation at this step through the scene and can be applied, e.g., to autonomous navigation. In the limit of observing real data at each point, our method converges to solving the SLAM problem. It can otherwise sample entirely imagined scenes from prior distributions. Besides autonomous agents, applications include problems where large data is required for building robust real-world applications, but few samples are available. We demonstrate efficacy on various 2D as well as 3D data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12297](http://arxiv.org/abs/1811.12297)

##### PDF
[http://arxiv.org/pdf/1811.12297](http://arxiv.org/pdf/1811.12297)

