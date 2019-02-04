---
layout: post
title: "Pixel-wise Ear Detection with Convolutional Encoder-Decoder Networks"
date: 2019-02-01 07:56:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection Recognition
author: &#x17d;iga Emer&#x161;i&#x10d;, Luka Lan Gabriel, Vitomir &#x160;truc, Peter Peer
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection and segmentation represents the basis for many tasks in computer and machine vision. In biometric recognition systems the detection of the region-of-interest (ROI) is one of the most crucial steps in the overall processing pipeline, significantly impacting the performance of the entire recognition system. Existing approaches to ear detection, for example, are commonly susceptible to the presence of severe occlusions, ear accessories or variable illumination conditions and often deteriorate in their performance if applied on ear images captured in unconstrained settings. To address these shortcomings, we present in this paper a novel ear detection technique based on convolutional encoder-decoder networks (CEDs). For our technique, we formulate the problem of ear detection as a two-class segmentation problem and train a convolutional encoder-decoder network based on the SegNet architecture to distinguish between image-pixels belonging to either the ear or the non-ear class. The output of the network is then post-processed to further refine the segmentation result and return the final locations of the ears in the input image. Different from competing techniques from the literature, our approach does not simply return a bounding box around the detected ear, but provides detailed, pixel-wise information about the location of the ears in the image. Our experiments on a dataset gathered from the web (a.k.a. in the wild) show that the proposed technique ensures good detection results in the presence of various covariate factors and significantly outperforms the existing state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1702.00307](http://arxiv.org/abs/1702.00307)

##### PDF
[http://arxiv.org/pdf/1702.00307](http://arxiv.org/pdf/1702.00307)

