---
layout: post
title: "Towards Multi-class Object Detection in Unconstrained Remote Sensing Imagery"
date: 2018-11-01 12:52:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Seyed Majid Azimi, Eleonora Vig, Reza Bahmanyar, Marco Körner, Peter Reinartz
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic multi-class object detection in remote sensing images in unconstrained scenarios is of high interest for several applications including traffic monitoring and disaster management. The huge variation in object scale, orientation, category, and complex backgrounds, as well as the different camera sensors pose great challenges for current algorithms. In this work, we propose a new method consisting of a novel joint image cascade and feature pyramid network with multi-size convolution kernels to extract multi-scale strong and weak semantic features. These features are fed into rotation-based region proposal and region of interest networks to produce object detections. Finally, rotational non-maximum suppression is applied to remove redundant detections. During training, we minimize joint horizontal and oriented bounding box loss functions, as well as a novel loss that enforces oriented boxes to be rectangular. Our method achieves 68.16% mAP on horizontal and 72.45% mAP on oriented bounding box detection tasks on the challenging DOTA dataset, outperforming all published methods by a large margin (+6% and +12% absolute improvement, respectively). Furthermore, it generalizes to two other datasets, NWPU VHR-10 and UCAS-AOD, and achieves competitive results with the baselines even when trained on DOTA. Our method can be deployed in multi-class object detection applications, regardless of the image and object scales and orientations, making it a great choice for unconstrained aerial and satellite imagery.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.02700](https://arxiv.org/abs/1807.02700)

##### PDF
[https://arxiv.org/pdf/1807.02700](https://arxiv.org/pdf/1807.02700)

