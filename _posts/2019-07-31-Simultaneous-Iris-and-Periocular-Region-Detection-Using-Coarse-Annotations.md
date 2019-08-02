---
layout: post
title: "Simultaneous Iris and Periocular Region Detection Using Coarse Annotations"
date: 2019-07-31 20:09:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection Recognition
author: Diego R. Lucio, Rayson Laroca, Luiz A. Zanlorensi, Gladston Moreira, David Menotti
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose to detect the iris and periocular regions simultaneously using coarse annotations and two well-known object detectors: YOLOv2 and Faster R-CNN. We believe coarse annotations can be used in recognition systems based on the iris and periocular regions, given the much smaller engineering effort required to manually annotate the training images. We manually made coarse annotations of the iris and periocular regions (122K images from the visible (VIS) spectrum and 38K images from the near-infrared (NIR) spectrum). The iris annotations in the NIR databases were generated semi-automatically by first applying an iris segmentation CNN and then performing a manual inspection. These annotations were made for 11 well-known public databases (3 NIR and 8 VIS) designed for the iris-based recognition problem and are publicly available to the research community. Experimenting our proposal on these databases, we highlight two results. First, the Faster R-CNN + Feature Pyramid Network (FPN) model reported an Intersection over Union (IoU) higher than YOLOv2 (91.86% vs 85.30%). Second, the detection of the iris and periocular regions being performed simultaneously is as accurate as performed separately, but with a lower computational cost, i.e., two tasks were carried out at the cost of one.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00069](http://arxiv.org/abs/1908.00069)

##### PDF
[http://arxiv.org/pdf/1908.00069](http://arxiv.org/pdf/1908.00069)

