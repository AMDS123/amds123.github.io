---
layout: post
title: "Fast detection of multiple objects in traffic scenes with a common detection framework"
date: 2015-10-12 02:30:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection Recognition
author: Qichang Hu, Sakrapee Paisitkriangkrai, Chunhua Shen, Anton van den Hengel, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
Traffic scene perception (TSP) aims to real-time extract accurate on-road environment information, which in- volves three phases: detection of objects of interest, recognition of detected objects, and tracking of objects in motion. Since recognition and tracking often rely on the results from detection, the ability to detect objects of interest effectively plays a crucial role in TSP. In this paper, we focus on three important classes of objects: traffic signs, cars, and cyclists. We propose to detect all the three important objects in a single learning based detection framework. The proposed framework consists of a dense feature extractor and detectors of three important classes. Once the dense features have been extracted, these features are shared with all detectors. The advantage of using one common framework is that the detection speed is much faster, since all dense features need only to be evaluated once in the testing phase. In contrast, most previous works have designed specific detectors using different features for each of these objects. To enhance the feature robustness to noises and image deformations, we introduce spatially pooled features as a part of aggregated channel features. In order to further improve the generalization performance, we propose an object subcategorization method as a means of capturing intra-class variation of objects. We experimentally demonstrate the effectiveness and efficiency of the proposed framework in three detection applications: traffic sign detection, car detection, and cyclist detection. The proposed framework achieves the competitive performance with state-of- the-art approaches on several benchmark datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1510.03125](https://arxiv.org/abs/1510.03125)

##### PDF
[https://arxiv.org/pdf/1510.03125](https://arxiv.org/pdf/1510.03125)

