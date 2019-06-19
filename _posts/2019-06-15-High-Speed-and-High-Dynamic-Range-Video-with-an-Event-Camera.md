---
layout: post
title: "High Speed and High Dynamic Range Video with an Event Camera"
date: 2019-06-15 04:56:14
categories: arXiv_CV
tags: arXiv_CV Classification
author: Henri Rebecq, Ren&#xe9; Ranftl, Vladlen Koltun, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
Event cameras are novel sensors that report brightness changes in the form of a stream of asynchronous "events" instead of intensity frames. They offer significant advantages with respect to conventional cameras: high temporal resolution, high dynamic range, and no motion blur. While the stream of events encodes in principle the complete visual signal, the reconstruction of an intensity image from a stream of events is an ill-posed problem in practice. Existing reconstruction approaches are based on hand-crafted priors and strong assumptions about the imaging process as well as the statistics of natural images. In this work we propose to learn to reconstruct intensity images from event streams directly from data instead of relying on any hand-crafted priors. We propose a novel recurrent network to reconstruct videos from a stream of events, and train it on a large amount of simulated event data. During training we propose to use a perceptual loss to encourage reconstructions to follow natural image statistics. We further extend our approach to synthesize color images from color event streams. Our network surpasses state-of-the-art reconstruction methods by a large margin in terms of image quality (&gt; 20%), while comfortably running in real-time. We show that the network is able to synthesize high framerate videos (&gt; 5,000 frames per second) of high-speed phenomena (e.g. a bullet hitting an object) and is able to provide high dynamic range reconstructions in challenging lighting conditions. We also demonstrate the effectiveness of our reconstructions as an intermediate representation for event data. We show that off-the-shelf computer vision algorithms can be applied to our reconstructions for tasks such as object classification and visual-inertial odometry and that this strategy consistently outperforms algorithms that were specifically designed for event data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07165](http://arxiv.org/abs/1906.07165)

##### PDF
[http://arxiv.org/pdf/1906.07165](http://arxiv.org/pdf/1906.07165)

