---
layout: post
title: "Video Salient Object Detection Using Spatiotemporal Deep Features"
date: 2018-06-18 01:49:28
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Segmentation Detection Relation
author: Trung-Nghia Le, Akihiro Sugimoto
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method for detecting salient objects in videos where temporal information in addition to spatial information is fully taken into account. Following recent reports on the advantage of deep features over conventional hand-crafted features, we propose a new set of SpatioTemporal Deep (STD) features that utilize local and global contexts over frames. We also propose new SpatioTemporal Conditional Random Field (STCRF) to compute saliency from STD features. STCRF is our extension of CRF to the temporal domain and describes the relationships among neighboring regions both in a frame and over frames. STCRF leads to temporally consistent saliency maps over frames, contributing to the accurate detection of salient objects' boundaries and noise reduction during detection. Our proposed method first segments an input video into multiple scales and then computes a saliency map at each scale level using STD features with STCRF. The final saliency map is computed by fusing saliency maps at different scale levels. Our experiments, using publicly available benchmark datasets, confirm that the proposed method significantly outperforms state-of-the-art methods. We also applied our saliency computation to the video object segmentation task, showing that our method outperforms existing video object segmentation methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.01447](https://arxiv.org/abs/1708.01447)

##### PDF
[https://arxiv.org/pdf/1708.01447](https://arxiv.org/pdf/1708.01447)

