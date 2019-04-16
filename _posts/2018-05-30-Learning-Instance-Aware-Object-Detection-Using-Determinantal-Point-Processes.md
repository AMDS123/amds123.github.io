---
layout: post
title: "Learning Instance-Aware Object Detection Using Determinantal Point Processes"
date: 2018-05-30 08:18:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Nuri Kim, Donghoon Lee, Songhwai Oh
mathjax: true
---

* content
{:toc}

##### Abstract
Recent object detectors find instances while categorizing candidate regions in an input image. As each region is evaluated independently, the number of candidate regions from a detector is usually larger than the number of objects. Since the final goal of detection is to assign a single detection to each object, an additional algorithm, such as non-maximum suppression (NMS), is used to select a single bounding box for an object. While simple heuristic algorithms, such as NMS, are effective for stand-alone objects, they can fail to detect overlapped objects. In this paper, we address this issue by training a network to distinguish different objects while localizing and categorizing them. We propose an instance-aware detection network (IDNet), which can learn to extract features from candidate regions and measures their similarities. Based on pairwise similarities and detection qualities, the IDNet selects an optimal subset of candidate bounding boxes using determinantal point processes (DPPs). Extensive experiments demonstrate that the proposed algorithm performs favorably compared to existing state-of-the-art detection methods particularly for overlapped objects on the PASCAL VOC and MS COCO datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.10765](https://arxiv.org/abs/1805.10765)

##### PDF
[https://arxiv.org/pdf/1805.10765](https://arxiv.org/pdf/1805.10765)

