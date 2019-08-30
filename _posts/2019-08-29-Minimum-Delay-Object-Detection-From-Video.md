---
layout: post
title: "Minimum Delay Object Detection From Video"
date: 2019-08-29 08:25:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Dong Lao, Ganesh Sundaramoorthi
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of detecting objects, as they come into view, from videos in an online fashion. We provide the first real-time solution that is guaranteed to minimize the delay, i.e., the time between when the object comes in view and the declared detection time, subject to acceptable levels of detection accuracy. The method leverages modern CNN-based object detectors that operate on a single frame, to aggregate detection results over frames to provide reliable detection at a rate, specified by the user, in guaranteed minimal delay. To do this, we formulate the problem as a Quickest Detection problem, which provides the aforementioned guarantees. We derive our algorithms from this theory. We show in experiments, that with an overhead of just 50 fps, we can increase the number of correct detections and decrease the overall computational cost compared to running a modern single-frame detector.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11092](http://arxiv.org/abs/1908.11092)

##### PDF
[http://arxiv.org/pdf/1908.11092](http://arxiv.org/pdf/1908.11092)

