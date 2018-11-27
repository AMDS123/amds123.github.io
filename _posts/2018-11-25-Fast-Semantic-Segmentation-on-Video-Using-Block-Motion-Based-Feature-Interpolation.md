---
layout: post
title: "Fast Semantic Segmentation on Video Using Block Motion-Based Feature Interpolation"
date: 2018-11-25 00:41:01
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN Semantic_Segmentation Inference Prediction
author: Samvit Jain, Joseph E. Gonzalez
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional networks optimized for accuracy on challenging, dense prediction tasks are prohibitively slow to run on each frame in a video. The spatial similarity of nearby video frames, however, suggests opportunity to reuse computation. Existing work has explored basic feature reuse and feature warping based on optical flow, but has encountered limits to the speedup attainable with these techniques. In this paper, we present a new, two part approach to accelerating inference on video. First, we propose a fast feature propagation technique that utilizes the block motion vectors present in compressed video (e.g. H.264 codecs) to cheaply propagate features from frame to frame. Second, we develop a novel feature estimation scheme, termed feature interpolation, that fuses features propagated from enclosing keyframes to render accurate feature estimates, even at sparse keyframe frequencies. We evaluate our system on the Cityscapes and CamVid datasets, comparing to both a frame-by-frame baseline and related work. We find that we are able to substantially accelerate segmentation on video, achieving near real-time frame rates (20.1 frames per second) on large images (960 x 720 pixels), while maintaining competitive accuracy. This represents an improvement of almost 6x over the single-frame baseline and 2.5x over the fastest prior work.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.07742](http://arxiv.org/abs/1803.07742)

##### PDF
[http://arxiv.org/pdf/1803.07742](http://arxiv.org/pdf/1803.07742)

