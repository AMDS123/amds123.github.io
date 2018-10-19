---
layout: post
title: "A Single-shot-per-pose Camera-Projector Calibration System For Imperfect Planar Targets"
date: 2018-10-17 19:43:56
categories: arXiv_CV
tags: arXiv_CV
author: Bingyao Huang, Samed Ozdemir, Ying Tang, Chunyuan Liao, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Existing camera-projector calibration methods typically warp feature points from a camera image to a projector image using estimated homographies, and often suffer from errors in camera parameters and noise due to imperfect planarity of the calibration target. In this paper we propose a simple yet robust solution that explicitly deals with these challenges. Following the structured light (SL) camera-project calibration framework, a carefully designed correspondence algorithm is built on top of the De Bruijn patterns. Such correspondence is then used for initial camera-projector calibration. Then, to gain more robustness against noises, especially those from an imperfect planar calibration board, a bundle adjustment algorithm is developed to jointly optimize the estimated camera and projector models. Aside from the robustness, our solution requires only one shot of SL pattern for each calibration board pose, which is much more convenient than multi-shot solutions in practice. Data validations are conducted on both synthetic and real datasets, and our method shows clear advantages over existing methods in all experiments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.09058](http://arxiv.org/abs/1803.09058)

##### PDF
[http://arxiv.org/pdf/1803.09058](http://arxiv.org/pdf/1803.09058)

