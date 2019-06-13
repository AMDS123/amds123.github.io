---
layout: post
title: "Wireless Software Synchronization of Multiple Distributed Cameras"
date: 2019-06-11 21:21:24
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Sameer Ansari, Neal Wadhwa, Rahul Garg, Jiawen Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for precisely time-synchronizing the capture of image sequences from a collection of smartphone cameras connected over WiFi. Our method is entirely software-based, has only modest hardware requirements, and achieves an accuracy of less than 250 microseconds on unmodified commodity hardware. It does not use image content and synchronizes cameras prior to capture. The algorithm operates in two stages. In the first stage, we designate one device as the leader and synchronize each client device's clock to it by estimating network delay. Once clocks are synchronized, the second stage initiates continuous image streaming, estimates the relative phase of image timestamps between each client and the leader, and shifts the streams into alignment. We quantitatively validate our results on a multi-camera rig imaging a high-precision LED array and qualitatively demonstrate significant improvements to multi-view stereo depth estimation and stitching of dynamic scenes. We release as open source 'libsoftwaresync', an Android implementation of our system, to inspire new types of collective capture applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09366](http://arxiv.org/abs/1812.09366)

##### PDF
[http://arxiv.org/pdf/1812.09366](http://arxiv.org/pdf/1812.09366)

