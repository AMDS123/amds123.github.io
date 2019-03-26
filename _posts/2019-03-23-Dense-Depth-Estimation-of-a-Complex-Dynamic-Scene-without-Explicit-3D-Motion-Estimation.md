---
layout: post
title: "Dense Depth Estimation of a Complex Dynamic Scene without Explicit 3D Motion Estimation"
date: 2019-03-23 10:15:21
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Suryansh Kumar, Ram Srivatsav Ghorakavi, Yuchao Dai, Hongdong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Recent geometric methods need reliable estimates of 3D motion parameters to procure accurate dense depth map of a complex dynamic scene from monocular images \cite{kumar2017monocular, ranftl2016dense}. Generally, to estimate \textbf{precise} measurements of relative 3D motion parameters and to validate its accuracy using image data is a challenging task. In this work, we propose an alternative approach that circumvents the 3D motion estimation requirement to obtain a dense depth map of a dynamic scene. Given per-pixel optical flow correspondences between two consecutive frames and, the sparse depth prior for the reference frame, we show that, we can effectively recover the dense depth map for the successive frames without solving for 3D motion parameters. Our method assumes a piece-wise planar model of a dynamic scene, which undergoes rigid transformation locally, and as-rigid-as-possible transformation globally between two successive frames. Under our assumption, we can avoid the explicit estimation of 3D rotation and translation to estimate scene depth. In essence, our formulation provides an unconventional way to think and recover the dense depth map of a complex dynamic scene which is incremental and motion free in nature. Our proposed method does not make object level or any other high-level prior assumption about the dynamic scene, as a result, it is applicable to a wide range of scenarios. Experimental results on the benchmarks dataset show the competence of our approach for multiple frames.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03791](http://arxiv.org/abs/1902.03791)

##### PDF
[http://arxiv.org/pdf/1902.03791](http://arxiv.org/pdf/1902.03791)

