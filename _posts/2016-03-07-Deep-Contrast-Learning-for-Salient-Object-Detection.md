---
layout: post
title: "Deep Contrast Learning for Salient Object Detection"
date: 2016-03-07 08:50:33
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Detection
author: Guanbin Li, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Salient object detection has recently witnessed substantial progress due to powerful features extracted using deep convolutional neural networks (CNNs). However, existing CNN-based methods operate at the patch level instead of the pixel level. Resulting saliency maps are typically blurry, especially near the boundary of salient objects. Furthermore, image patches are treated as independent samples even when they are overlapping, giving rise to significant redundancy in computation and storage. In this CVPR 2016 paper, we propose an end-to-end deep contrast network to overcome the aforementioned limitations. Our deep network consists of two complementary components, a pixel-level fully convolutional stream and a segment-wise spatial pooling stream. The first stream directly produces a saliency map with pixel-level accuracy from an input image. The second stream extracts segment-wise features very efficiently, and better models saliency discontinuities along object boundaries. Finally, a fully connected CRF model can be optionally incorporated to improve spatial coherence and contour localization in the fused result from these two streams. Experimental results demonstrate that our deep model significantly improves the state of the art.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1603.01976](https://arxiv.org/abs/1603.01976)

##### PDF
[https://arxiv.org/pdf/1603.01976](https://arxiv.org/pdf/1603.01976)

