---
layout: post
title: "Event-driven Video Frame Synthesis"
date: 2019-02-26 00:54:09
categories: arXiv_CV
tags: arXiv_CV Optimization Gradient_Descent
author: Zihao Wang, Weixin Jiang, Aggelos Katsaggelos, Oliver Cossairt
mathjax: true
---

* content
{:toc}

##### Abstract
Video frame synthesis is an active computer vision problem which has applications in video compression, streaming, editing, and understanding. In this work, we present a computational high speed video synthesis framework. Our framework takes as inputs two types of data streams: an intensity frame stream and a neuromorphic event stream, which consists of asynchronous bipolar "events" which encode brightness variations over time at over 1000 fps. We introduce an algorithm to recover a space-time video from these two modes of observations. We factor the reconstruction into a physical model-based reconstruction (PBR) process and a residual denoising process. We use a differentiable model to approximate the physical sensing process, which enables stochastic gradient descent optimization using automatic differentiation. Residual errors in PBR reconstruction are further reduced by training a residual denoiser to remove reconstruction artifacts. The video output from our reconstruction algorithm has both high frame rate and well-recovered spatial features. Our framework is capable of handling challenging scenes that include fast motion and strong occlusions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09680](http://arxiv.org/abs/1902.09680)

##### PDF
[http://arxiv.org/pdf/1902.09680](http://arxiv.org/pdf/1902.09680)

