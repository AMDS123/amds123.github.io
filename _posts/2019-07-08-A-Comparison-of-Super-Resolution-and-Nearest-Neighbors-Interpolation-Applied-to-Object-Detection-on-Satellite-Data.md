---
layout: post
title: "A Comparison of Super-Resolution and Nearest Neighbors Interpolation Applied to Object Detection on Satellite Data"
date: 2019-07-08 17:03:12
categories: arXiv_AI
tags: arXiv_AI Super_Resolution Object_Detection Classification Detection
author: Evan Koester, Cem Safak Sahin
mathjax: true
---

* content
{:toc}

##### Abstract
As Super-Resolution (SR) has matured as a research topic, it has been applied to additional topics beyond image reconstruction. In particular, combining classification or object detection tasks with a super-resolution preprocessing stage has yielded improvements in accuracy especially with objects that are small relative to the scene. While SR has shown promise, a study comparing SR and naive upscaling methods such as Nearest Neighbors (NN) interpolation when applied as a preprocessing step for object detection has not been performed. We apply the topic to satellite data and compare the Multi-scale Deep Super-Resolution (MDSR) system to NN on the xView challenge dataset. To do so, we propose a pipeline for processing satellite data that combines multi-stage image tiling and upscaling, the YOLOv2 object detection architecture, and label stitching. We compare the effects of training models using an upscaling factor of 4, upscaling images from 30cm Ground Sample Distance (GSD) to an effective GSD of 7.5cm. Upscaling by this factor significantly improves detection results, increasing Average Precision (AP) of a generalized vehicle class by 23 percent. We demonstrate that while SR produces upscaled images that are more visually pleasing than their NN counterparts, object detection networks see little difference in accuracy with images upsampled using NN obtaining nearly identical results to the MDSRx4 enhanced images with a difference of 0.0002 AP between the two methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05283](http://arxiv.org/abs/1907.05283)

##### PDF
[http://arxiv.org/pdf/1907.05283](http://arxiv.org/pdf/1907.05283)

