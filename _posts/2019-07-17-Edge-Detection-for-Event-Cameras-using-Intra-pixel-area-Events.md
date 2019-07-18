---
layout: post
title: "Edge Detection for Event Cameras using Intra-pixel-area Events"
date: 2019-07-17 12:28:32
categories: arXiv_RO
tags: arXiv_RO Sparse Face Quantitative Detection
author: Sangil Lee, Haram Kim, H. Jin Kim
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose an edge detection algorithm by estimating a lifetime of an event produced from dynamic vision sensor (DVS), also known as event camera. The event camera, unlike traditional CMOS camera, generates sparse event data at a pixel whose log-intensity changes. Due to this characteristic, theoretically, there is only one or no event at the specific time, which makes it difficult to grasp the world captured by the camera at a particular moment. In this work, we present an algorithm that keeps the event alive until the corresponding event is generated in a nearby pixel so that the shape of an edge is preserved. Particularly, we consider a pixel area to fit a plane on Surface of Active Events (SAE) and call the point inside the pixel area closest to the plane as a intra-pixel-area event. These intra-pixel-area events help the fitting plane algorithm to estimate life time robustly and precisely. Our algorithm performs better in terms of sharpness and similarity metric than the accumulation of events over fixed counts or time intervals, when compared with the existing edge detection algorithms, both qualitatively and quantitatively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07469](http://arxiv.org/abs/1907.07469)

##### PDF
[http://arxiv.org/pdf/1907.07469](http://arxiv.org/pdf/1907.07469)

