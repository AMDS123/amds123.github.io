---
layout: post
title: "Object Detection by Spatio-Temporal Analysis and Tracking of the Detected Objects in a Video with Variable Background"
date: 2017-04-28 09:32:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection
author: Kumar S. Ray, Vijayan K. Asari, Soma Chakraborty
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a novel approach for detecting and tracking objects in videos with variable background i.e. videos captured by moving cameras without any additional sensor. In a video captured by a moving camera, both the background and foreground are changing in each frame of the image sequence. So for these videos, modeling a single background with traditional background modeling methods is infeasible and thus the detection of actual moving object in a variable background is a challenging task. To detect actual moving object in this work, spatio-temporal blobs have been generated in each frame by spatio-temporal analysis of the image sequence using a three-dimensional Gabor filter. Then individual blobs, which are parts of one object are merged using Minimum Spanning Tree to form the moving object in the variable background. The height, width and four-bin gray-value histogram of the object are calculated as its features and an object is tracked in each frame using these features to generate the trajectories of the object through the video sequence. In this work, problem of data association during tracking is solved by Linear Assignment Problem and occlusion is handled by the application of kalman filter. The major advantage of our method over most of the existing tracking algorithms is that, the proposed method does not require initialization in the first frame or training on sample data to perform. Performance of the algorithm has been tested on benchmark videos and very satisfactory result has been achieved. The performance of the algorithm is also comparable and superior with respect to some benchmark algorithms.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.02949](https://arxiv.org/abs/1705.02949)

##### PDF
[https://arxiv.org/pdf/1705.02949](https://arxiv.org/pdf/1705.02949)

