---
layout: post
title: "An Efficient Approach for Object Detection and Tracking of Objects in a Video with Variable Background"
date: 2017-05-11 08:23:35
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection Relation
author: Kumar S. Ray, Soma Chakraborty
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel approach to create an automated visual surveillance system which is very efficient in detecting and tracking moving objects in a video captured by moving camera without any apriori information about the captured scene. Separating foreground from the background is challenging job in videos captured by moving camera as both foreground and background information change in every consecutive frames of the image sequence; thus a pseudo-motion is perceptive in background. In the proposed algorithm, the pseudo-motion in background is estimated and compensated using phase correlation of consecutive frames based on the principle of Fourier shift theorem. Then a method is proposed to model an acting background from recent history of commonality of the current frame and the foreground is detected by the differences between the background model and the current frame. Further exploiting the recent history of dissimilarities of the current frame, actual moving objects are detected in the foreground. Next, a two-stepped morphological operation is proposed to refine the object region for an optimum object size. Each object is attributed by its centroid, dimension and three highest peaks of its gray value histogram. Finally, each object is tracked using Kalman filter based on its attributes. The major advantage of this algorithm over most of the existing object detection and tracking algorithms is that, it does not require initialization of object position in the first frame or training on sample data to perform. Performance of the algorithm is tested on benchmark videos containing variable background and very satisfiable results is achieved. The performance of the algorithm is also comparable with some of the state-of-the-art algorithms for object detection and tracking.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.02672](https://arxiv.org/abs/1706.02672)

##### PDF
[https://arxiv.org/pdf/1706.02672](https://arxiv.org/pdf/1706.02672)

