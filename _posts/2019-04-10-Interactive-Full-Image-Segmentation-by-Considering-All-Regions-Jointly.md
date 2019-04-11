---
layout: post
title: "Interactive Full Image Segmentation by Considering All Regions Jointly"
date: 2019-04-10 15:51:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction
author: Eirikur Agustsson, Jasper R. R. Uijlings, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We address interactive full image annotation, where the goal is to accurately segment all object and stuff regions in an image. We propose an interactive, scribble-based annotation framework which operates on the whole image to produce segmentations for all regions. This enables sharing scribble corrections across regions, and allows the annotator to focus on the largest errors made by the machine across the whole image. To realize this, we adapt Mask-RCNN into a fast interactive segmentation framework and introduce an instance-aware loss measured at the pixel-level in the full image canvas, which lets predictions for nearby regions properly compete for space. Finally, we compare to interactive single object segmentation on the COCO panoptic dataset. We demonstrate that our interactive full image segmentation approach leads to a 5% IoU gain, reaching 90% IoU at a budget of four extreme clicks and four corrective scribbles per region.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01888](http://arxiv.org/abs/1812.01888)

##### PDF
[http://arxiv.org/pdf/1812.01888](http://arxiv.org/pdf/1812.01888)

