---
layout: post
title: "Deep Flow-Guided Video Inpainting"
date: 2019-05-08 03:27:15
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Rui Xu, Xiaoxiao Li, Bolei Zhou, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
Video inpainting, which aims at filling in missing regions of a video, remains challenging due to the difficulty of preserving the precise spatial and temporal coherence of video contents. In this work we propose a novel flow-guided video inpainting approach. Rather than filling in the RGB pixels of each frame directly, we consider video inpainting as a pixel propagation problem. We first synthesize a spatially and temporally coherent optical flow field across video frames using a newly designed Deep Flow Completion network. Then the synthesized flow field is used to guide the propagation of pixels to fill up the missing regions in the video. Specifically, the Deep Flow Completion network follows a coarse-to-fine refinement to complete the flow fields, while their quality is further improved by hard flow example mining. Following the guide of the completed flow, the missing video regions can be filled up precisely. Our method is evaluated on DAVIS and YouTube-VOS datasets qualitatively and quantitatively, achieving the state-of-the-art performance in terms of inpainting quality and speed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02884](http://arxiv.org/abs/1905.02884)

##### PDF
[http://arxiv.org/pdf/1905.02884](http://arxiv.org/pdf/1905.02884)

