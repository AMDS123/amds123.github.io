---
layout: post
title: "Cascade R-CNN: High Quality Object Detection and Instance Segmentation"
date: 2019-06-24 07:22:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Face Inference Detection
author: Zhaowei Cai, Nuno Vasconcelos
mathjax: true
---

* content
{:toc}

##### Abstract
In object detection, the intersection over union (IoU) threshold is frequently used to define positives/negatives. The threshold used to train a detector defines its \textit{quality}. While the commonly used threshold of 0.5 leads to noisy (low-quality) detections, detection performance frequently degrades for larger thresholds. This paradox of high-quality detection has two causes: 1) overfitting, due to vanishing positive samples for large thresholds, and 2) inference-time quality mismatch between detector and test hypotheses. A multi-stage object detection architecture, the Cascade R-CNN, composed of a sequence of detectors trained with increasing IoU thresholds, is proposed to address these problems. The detectors are trained sequentially, using the output of a detector as training set for the next. This resampling progressively improves hypotheses quality, guaranteeing a positive training set of equivalent size for all detectors and minimizing overfitting. The same cascade is applied at inference, to eliminate quality mismatches between hypotheses and detectors. An implementation of the Cascade R-CNN without bells or whistles achieves state-of-the-art performance on the COCO dataset, and significantly improves high-quality detection on generic and specific object detection datasets, including VOC, KITTI, CityPerson, and WiderFace. Finally, the Cascade R-CNN is generalized to instance segmentation, with nontrivial improvements over the Mask R-CNN. To facilitate future research, two implementations are made available at \url{https://github.com/zhaoweicai/cascade-rcnn} (Caffe) and \url{https://github.com/zhaoweicai/Detectron-Cascade-RCNN} (Detectron).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09756](http://arxiv.org/abs/1906.09756)

##### PDF
[http://arxiv.org/pdf/1906.09756](http://arxiv.org/pdf/1906.09756)

