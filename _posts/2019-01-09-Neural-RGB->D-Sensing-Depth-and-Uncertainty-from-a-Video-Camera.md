---
layout: post
title: "Neural RGB->D Sensing: Depth and Uncertainty from a Video Camera"
date: 2019-01-09 01:14:46
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Chao Liu, Jinwei Gu, Kihwan Kim, Srinivasa Narasimhan, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Depth sensing is crucial for 3D reconstruction and scene understanding. Active depth sensors provide dense metric measurements, but often suffer from limitations such as restricted operating ranges, low spatial resolution, sensor interference, and high power consumption. In this paper, we propose a deep learning (DL) method to estimate per-pixel depth and its uncertainty continuously from a monocular video stream, with the goal of effectively turning an RGB camera into an RGB-D camera. Unlike prior DL-based methods, we estimate a depth probability distribution for each pixel rather than a single depth value, leading to an estimate of a 3D depth probability volume for each input frame. These depth probability volumes are accumulated over time under a Bayesian filtering framework as more incoming frames are processed sequentially, which effectively reduces depth uncertainty and improves accuracy, robustness, and temporal stability. Compared to prior work, the proposed approach achieves more accurate and stable results, and generalizes better to new datasets. Experimental results also show the output of our approach can be directly fed into classical RGB-D based 3D scanning methods for 3D scene reconstruction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02571](http://arxiv.org/abs/1901.02571)

##### PDF
[http://arxiv.org/pdf/1901.02571](http://arxiv.org/pdf/1901.02571)

