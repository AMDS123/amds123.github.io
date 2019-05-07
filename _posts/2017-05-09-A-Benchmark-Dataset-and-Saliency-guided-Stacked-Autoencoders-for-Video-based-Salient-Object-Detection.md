---
layout: post
title: "A Benchmark Dataset and Saliency-guided Stacked Autoencoders for Video-based Salient Object Detection"
date: 2017-05-09 07:38:17
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Knowledge Tracking Deep_Learning Detection
author: Jia Li, Changqun Xia, Xiaowu Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Image-based salient object detection (SOD) has been extensively studied in the past decades. However, video-based SOD is much less explored since there lack large-scale video datasets within which salient objects are unambiguously defined and annotated. Toward this end, this paper proposes a video-based SOD dataset that consists of 200 videos (64 minutes). In constructing the dataset, we manually annotate all objects and regions over 7,650 uniformly sampled keyframes and collect the eye-tracking data of 23 subjects that free-view all videos. From the user data, we find salient objects in video can be defined as objects that consistently pop-out throughout the video, and objects with such attributes can be unambiguously annotated by combining manually annotated object/region masks with eye-tracking data of multiple subjects. To the best of our knowledge, it is currently the largest dataset for video-based salient object detection. Based on this dataset, this paper proposes an unsupervised baseline approach for video-based SOD by using saliency-guided stacked autoencoders. In the proposed approach, multiple spatiotemporal saliency cues are first extracted at pixel, superpixel and object levels. With these saliency cues, stacked autoencoders are unsupervisedly constructed which automatically infer a saliency score for each pixel by progressively encoding the high-dimensional saliency cues gathered from the pixel and its spatiotemporal neighbors. Experimental results show that the proposed unsupervised approach outperforms 30 state-of-the-art models on the proposed dataset, including 19 image-based & classic (unsupervised or non-deep learning), 6 image-based & deep learning, and 5 video-based & unsupervised. Moreover, benchmarking results show that the proposed dataset is very challenging and has the potential to boost the development of video-based SOD.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1611.00135](https://arxiv.org/abs/1611.00135)

##### PDF
[https://arxiv.org/pdf/1611.00135](https://arxiv.org/pdf/1611.00135)

