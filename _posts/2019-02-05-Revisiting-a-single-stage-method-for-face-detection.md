---
layout: post
title: "Revisiting a single-stage method for face detection"
date: 2019-02-05 06:02:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Inference Detection Face_Detection
author: Nguyen Van Quang, Hiromasa Fujihara
mathjax: true
---

* content
{:toc}

##### Abstract
Although accurate, two-stage face detectors usually require more inference time than single-stage detectors do. This paper proposes a simple yet effective single-stage model for real-time face detection with a prominently high accuracy. We build our single-stage model on the top of the ResNet-101 backbone and analyze some problems with the baseline single-stage detector in order to design several strategies for reducing the false positive rate. The design leverages the context information from the deeper layers in order to increase recall rate while maintaining a low false positive rate. In addition, we reduce the detection time by an improved inference procedure for decoding outputs faster. The inference time of a VGA ($640{\times}480$) image was only approximately 26 ms with a Titan X GPU. The effectiveness of our proposed method was evaluated on several face detection benchmarks (Wider Face, AFW, Pascal Face, and FDDB). The experiments show that our method achieved competitive results on these popular datasets with a faster runtime than the current best two-stage practices.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01559](http://arxiv.org/abs/1902.01559)

##### PDF
[http://arxiv.org/pdf/1902.01559](http://arxiv.org/pdf/1902.01559)

