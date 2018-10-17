---
layout: post
title: "Let's take a Walk on Superpixels Graphs: Deformable Linear Objects Segmentation and Model Estimation"
date: 2018-10-10 11:31:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation CNN Semantic_Segmentation Detection
author: Daniele De Gregorio, Gianluca Palli, Luigi Di Stefano
mathjax: true
---

* content
{:toc}

##### Abstract
While robotic manipulation of rigid objects is quite straightforward, coping with deformable objects is an open issue. More specifically, tasks like tying a knot, wiring a connector or even surgical suturing deal with the domain of Deformable Linear Objects (DLOs). In particular the detection of a DLO is a non-trivial problem especially under clutter and occlusions (as well as self-occlusions). The pose estimation of a DLO results into the identification of its parameters related to a designed model, e.g. a basis spline. It follows that the stand-alone segmentation of a DLO might not be sufficient to conduct a full manipulation task. This is why we propose a novel framework able to perform both a semantic segmentation and b-spline modeling of multiple deformable linear objects simultaneously without strict requirements about environment (i.e. the background). The core algorithm is based on biased random walks over the Region Adiacency Graph built on a superpixel oversegmentation of the source image. The algorithm is initialized by a Convolutional Neural Networks that detects the DLO's endcaps. An open source implementation of the proposed approach is also provided to easy the reproduction of the whole detection pipeline along with a novel cables dataset in order to encourage further experiments.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.04461](https://arxiv.org/abs/1810.04461)

##### PDF
[https://arxiv.org/pdf/1810.04461](https://arxiv.org/pdf/1810.04461)

