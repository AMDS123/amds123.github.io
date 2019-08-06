---
layout: post
title: "Image-Guided Depth Sampling and Reconstruction"
date: 2019-08-04 17:55:47
categories: arXiv_CV
tags: arXiv_CV Detection
author: Adam Wolff, Shachar Praisler, Ilya Tcenov, Guy Gilboa
mathjax: true
---

* content
{:toc}

##### Abstract
Depth acquisition, based on active illumination, is essential for autonomous and robotic navigation. LiDARs (Light Detection And Ranging) with mechanical, fixed, sampling templates are commonly used in today's autonomous vehicles. An emerging technology, based on solid-state depth sensors, with no mechanical parts, allows fast, adaptive, programmable scans. 
 In this paper, we investigate the topic of adaptive, image-driven, sampling and reconstruction strategies. First, we formulate a piece-wise linear depth model with several tolerance parameters and estimate its validity for indoor and outdoor scenes. Our model and experiments predict that, in the optimal case, about 20-60 piece-wise linear structures can approximate well a depth map. This translates to a depth-to-image sampling ratio of about 1/1200. We propose a simple, generic, sampling and reconstruction algorithm, based on super-pixels. We reach a sampling rate which is still far from the optimal case. However, our sampling improves grid and random sampling, consistently, for a wide variety of reconstruction methods. Moreover, our proposed reconstruction achieves state-of-the-art results, compared to image-guided depth completion algorithms, reducing the required sampling rate by a factor of 3-4. A single-pixel depth camera built in our lab illustrates the concept.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01379](http://arxiv.org/abs/1908.01379)

##### PDF
[http://arxiv.org/pdf/1908.01379](http://arxiv.org/pdf/1908.01379)

