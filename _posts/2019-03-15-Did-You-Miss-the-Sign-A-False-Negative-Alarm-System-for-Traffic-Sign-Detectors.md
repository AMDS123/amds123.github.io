---
layout: post
title: "Did You Miss the Sign? A False Negative Alarm System for Traffic Sign Detectors"
date: 2019-03-15 07:34:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection Recognition
author: Quazi Marufur Rahman, Niko S&#xfc;nderhauf, Feras Dayoub
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is an integral part of an autonomous vehicle for its safety-critical and navigational purposes. Traffic signs as objects play a vital role in guiding such systems. However, if the vehicle fails to locate any critical sign, it might make a catastrophic failure. In this paper, we propose an approach to identify traffic signs that have been mistakenly discarded by the object detector. The proposed method raises an alarm when it discovers a failure by the object detector to detect a traffic sign. This approach can be useful to evaluate the performance of the detector during the deployment phase. We trained a single shot multi-box object detector to detect traffic signs and used its internal features to train a separate false negative detector (FND). During deployment, FND decides whether the traffic sign detector (TSD) has missed a sign or not. We are using precision and recall to measure the accuracy of FND in two different datasets. For 80% recall, FND has achieved 89.9% precision in Belgium Traffic Sign Detection dataset and 90.8% precision in German Traffic Sign Recognition Benchmark dataset respectively. To the best of our knowledge, our method is the first to tackle this critical aspect of false negative detection in robotic vision. Such a fail-safe mechanism for object detection can improve the engagement of robotic vision systems in our daily life.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06391](http://arxiv.org/abs/1903.06391)

##### PDF
[http://arxiv.org/pdf/1903.06391](http://arxiv.org/pdf/1903.06391)

