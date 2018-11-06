---
layout: post
title: "ReXCam: Resource-Efficient, Cross-Camera Video Analytics at Enterprise Scale"
date: 2018-11-03 19:15:15
categories: arXiv_CV
tags: arXiv_CV Inference Detection Relation
author: Samvit Jain, Junchen Jiang, Yuanchao Shu, Ganesh Ananthanarayanan, Joseph Gonzalez
mathjax: true
---

* content
{:toc}

##### Abstract
The deployment of large camera networks for video analytics is an established and accelerating trend. Many real video inference applications entail a common problem template: searching for an object or activity of interest (e.g. a person, a speeding vehicle) through a large camera network in live video. This capability, called cross-camera analytics, is compute and data intensive -- requiring automated search across cameras and across frames, at the throughput of the live video stream. To address the cost challenge of processing every raw video frame from a large deployment, we present ReXCam, a new system for efficient cross-camera video analytics. ReXCam exploits spatial and temporal locality in the dynamics of real camera networks to guide its inference-time search for a query identity. In an offline profiling phase, ReXCam builds a cross-camera correlation model that encodes the locality observed in historical traffic patterns. At inference time, ReXCam applies this model to filter frames that are not spatially and temporally correlated with the query identity's current position. In the cases of occasional missed detections, ReXCam performs a fast-replay search on recently filtered video frames, enabling gracefully recovery. Together, these techniques allow ReXCam to reduce compute workload by 4.6x and improve inference precision by 27% on a well-known video dataset with footage from eight cameras, while maintaining within 1-2% of baseline recall.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01268](http://arxiv.org/abs/1811.01268)

##### PDF
[http://arxiv.org/pdf/1811.01268](http://arxiv.org/pdf/1811.01268)

