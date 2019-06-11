---
layout: post
title: "Unsupervised Temperature Scaling: An Unsupervised Post-Processing Calibration Method of Deep Networks"
date: 2019-06-10 15:23:22
categories: arXiv_CV
tags: arXiv_CV Inference Deep_Learning Detection
author: Azadeh Sadat Mozafari, Hugo Siqueira Gomes, Wilson Le&#xe3;o, Christian Gagn&#xe9;
mathjax: true
---

* content
{:toc}

##### Abstract
The great performances of deep learning are undeniable, with impressive results over a wide range of tasks. However, the output confidence of these models is usually not well-calibrated, which can be an issue for applications where confidence on the decisions is central to providing trust and reliability (e.g., autonomous driving or medical diagnosis). For models using softmax at the last layer, Temperature Scaling (TS) is a state-of-the-art calibration method, with low time and memory complexity as well as demonstrated effectiveness. TS relies on a T parameter to rescale and calibrate values of the softmax layer, whose parameter value is computed from a labelled dataset. We are proposing an Unsupervised Temperature Scaling (UTS) approach, which does not depend on labelled samples to calibrate the model, which allows, for example, the use of a part of a test samples to calibrate the pre-trained model before going into inference mode. We provide theoretical justifications for UTS and assess its effectiveness on a wide range of deep models and datasets. We also demonstrate calibration results of UTS on skin lesion detection, a problem where a well-calibrated output can play an important role for accurate decision-making.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00174](http://arxiv.org/abs/1905.00174)

##### PDF
[http://arxiv.org/pdf/1905.00174](http://arxiv.org/pdf/1905.00174)

