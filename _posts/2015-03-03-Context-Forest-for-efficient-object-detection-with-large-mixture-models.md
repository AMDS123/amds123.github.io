---
layout: post
title: "Context Forest for efficient object detection with large mixture models"
date: 2015-03-03 00:20:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Davide Modolo, Alexander Vezhnevets, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We present Context Forest (ConF), a technique for predicting properties of the objects in an image based on its global appearance. Compared to standard nearest-neighbour techniques, ConF is more accurate, fast and memory efficient. We train ConF to predict which aspects of an object class are likely to appear in a given image (e.g. which viewpoint). This enables to speed-up multi-component object detectors, by automatically selecting the most relevant components to run on that image. This is particularly useful for detectors trained from large datasets, which typically need many components to fully absorb the data and reach their peak performance. ConF provides a speed-up of 2x for the DPM detector [1] and of 10x for the EE-SVM detector [2]. To show ConF's generality, we also train it to predict at which locations objects are likely to appear in an image. Incorporating this information in the detector score improves mAP performance by about 2% by removing false positive detections in unlikely locations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1503.00787](https://arxiv.org/abs/1503.00787)

##### PDF
[https://arxiv.org/pdf/1503.00787](https://arxiv.org/pdf/1503.00787)

