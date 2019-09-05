---
layout: post
title: "Aerial multi-object tracking by detection using deep association networks"
date: 2019-09-04 03:52:37
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Drone Object_Tracking Deep_Learning Detection
author: Ajit Jadhav, Prerana Mukherjee, Vinay Kaushik, Brejesh Lall
mathjax: true
---

* content
{:toc}

##### Abstract
A lot a research is focused on object detection and it has achieved significant advances with deep learning techniques in recent years. Inspite of the existing research, these algorithms are not usually optimal for dealing with sequences or images captured by drone-based platforms, due to various challenges such as view point change, scales, density of object distribution and occlusion. In this paper, we develop a model for detection of objects in drone images using the VisDrone2019 DET dataset. Using the RetinaNet model as our base, we modify the anchor scales to better handle the detection of dense distribution and small size of the objects. We explicitly model the channel interdependencies by using "Squeeze-and-Excitation" (SE) blocks that adaptively recalibrates channel-wise feature responses. This helps to bring significant improvements in performance at a slight additional computational cost. Using this architecture for object detection, we build a custom DeepSORT network for object detection on the VisDrone2019 MOT dataset by training a custom Deep Association network for the algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01547](http://arxiv.org/abs/1909.01547)

##### PDF
[http://arxiv.org/pdf/1909.01547](http://arxiv.org/pdf/1909.01547)

