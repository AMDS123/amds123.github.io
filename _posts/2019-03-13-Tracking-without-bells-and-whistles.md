---
layout: post
title: "Tracking without bells and whistles"
date: 2019-03-13 17:45:49
categories: arXiv_CV
tags: arXiv_CV Re-identification Object_Detection Tracking Object_Tracking Optimization Prediction Detection
author: Philipp Bergmann, Tim Meinhardt, Laura Leal-Taixe
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of tracking multiple objects in a video sequence poses several challenging tasks. For tracking-by-detection these include, among others, object re-identification, motion prediction and dealing with occlusions. We present a tracker without bells and whistles that accomplishes tracking without specifically targeting any of these tasks, in particular, we perform no training or optimization on tracking data. To this end, we exploit the bounding box regression of an object detector to predict an object's new position in the next frame, thereby converting a detector into a Tracktor. We demonstrate the extensibility of our Tracktor and provide a new state-of-the-art on three multi-object tracking benchmarks by extending it with a straightforward re-identification and camera motion compensation. 
 We then perform an analysis on the performance and failure cases of several state-of-the-art tracking methods and our Tracktor. Surprisingly, none of the dedicated tracking methods are considerably better in dealing with complex tracking scenarios, namely, small and occluded objects or missing detections. However, our approach tackles most of the easy tracking scenarios. Therefore, we motivate our approach as a new tracking paradigm and point out promising future research directions. Overall, we show that a cleverly exploited detector can perform better tracking than any current tracking method and expose the real tracking challenges which are still unsolved.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05625](http://arxiv.org/abs/1903.05625)

##### PDF
[http://arxiv.org/pdf/1903.05625](http://arxiv.org/pdf/1903.05625)

