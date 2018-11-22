---
layout: post
title: "Real-Time 6D Object Pose Estimation on CPU"
date: 2018-11-21 03:42:20
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Yoshinori Konishi, Kosuke Hattori, Manabu Hashimoto
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a fast and accurate 6D object pose estimation from a RGB-D image. Our proposed method is template matching based and consists of three main technical components, PCOF-MOD (multimodal PCOF), balanced pose tree (BPT) and optimum memory rearrangement for a coarse-to-fine search. Our model templates on densely sampled viewpoints and PCOF-MOD which explicitly handles a certain range of 3D object pose improve the robustness against background clutters. BPT which is an efficient tree-based data structures for a large number of templates and template matching on rearranged feature maps where nearby features are linearly aligned accelerate the pose estimation. The experimental evaluation on tabletop and bin-picking dataset showed that our method achieved higher accuracy and faster speed in comparison with state-of-the-art techniques including recent CNN based approaches. Moreover, our model templates can be trained only from 3D CAD in a few minutes and the pose estimation run in near real-time (23 fps) on CPU. These features are suitable for any real applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08588](http://arxiv.org/abs/1811.08588)

##### PDF
[http://arxiv.org/pdf/1811.08588](http://arxiv.org/pdf/1811.08588)

