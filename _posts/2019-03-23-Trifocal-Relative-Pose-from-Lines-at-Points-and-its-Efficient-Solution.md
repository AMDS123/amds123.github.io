---
layout: post
title: "Trifocal Relative Pose from Lines at Points and its Efficient Solution"
date: 2019-03-23 04:26:57
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Ricardo Fabbri, Timothy Duff, Hongyi Fan, Margaret Regan, David da Costa de Pinho, Elias Tsigaridas, Charles Wrampler, Jonathan Hauenstein, Benjamin Kimia, Anton Leykin, Tomas Pajdla
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new minimal problem for relative pose estimation mixing point features with lines incident at points observed in three views and its efficient homotopy continuation solver. We demonstrate the generality of the approach by analyzing and solving an additional trifocal problem with mixed points and line correspondences in three views. The minimal problems include correspondences across three views of (i) three points and one line and (ii) three points and two lines through two of the points which is reported and analyzed here for the first time. These are difficult to solve, as they have 216 and -- as shown here -- 312 solutions, but cover important practical situations when line and point features appear together, \eg, in urban scenes or when observing curves. We demonstrate that even such difficult problems can be solved robustly using a suitable homotopy continuation technique and we provide an implementation optimized for minimal problems that can be integrated into engineering applications. Our simulated and real experiments demonstrate our solvers in the camera geometry computation task in structure from motion. We show that new solvers allow for reconstructing challenging scenes where the standard two-view initialization of structure from motion fails.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09755](http://arxiv.org/abs/1903.09755)

##### PDF
[http://arxiv.org/pdf/1903.09755](http://arxiv.org/pdf/1903.09755)

