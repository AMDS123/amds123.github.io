---
layout: post
title: "You Only Look Twice: Rapid Multi-Scale Object Detection In Satellite Imagery"
date: 2018-05-24 05:17:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Adam Van Etten
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of small objects in large swaths of imagery is one of the primary problems in satellite imagery analytics. While object detection in ground-based imagery has benefited from research into new deep learning approaches, transitioning such technology to overhead imagery is nontrivial. Among the challenges is the sheer number of pixels and geographic extent per image: a single DigitalGlobe satellite image encompasses >64 km2 and over 250 million pixels. Another challenge is that objects of interest are minuscule (often only ~10 pixels in extent), which complicates traditional computer vision techniques. To address these issues, we propose a pipeline (You Only Look Twice, or YOLT) that evaluates satellite images of arbitrary size at a rate of >0.5 km2/s. The proposed approach can rapidly detect objects of vastly different scales with relatively little training data over multiple sensors. We evaluate large test images at native resolution, and yield scores of F1 > 0.8 for vehicle localization. We further explore resolution and object size requirements by systematically testing the pipeline at decreasing resolution, and conclude that objects only ~5 pixels in size can still be localized with high confidence. Code is available at this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.09512](https://arxiv.org/abs/1805.09512)

##### PDF
[https://arxiv.org/pdf/1805.09512](https://arxiv.org/pdf/1805.09512)

