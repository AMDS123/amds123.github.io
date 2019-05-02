---
layout: post
title: "Unsupervised Temperature Scaling: Post-Processing Unsupervised Calibration of Deep Models Decisions"
date: 2019-05-01 03:43:29
categories: arXiv_CV
tags: arXiv_CV Inference Deep_Learning Detection
author: Azadeh Sadat Mozafari, Hugo Siqueira Gomes, Wilson Le&#xe3;o, Christian Gagn&#xe9;
mathjax: true
---

* content
{:toc}

##### Abstract
Great performances of deep learning are undeniable, with impressive results on wide range of tasks. However, the output confidence of these models is usually not well calibrated, which can be an issue for applications where confidence on the decisions is central to bring trust and reliability (e.g., autonomous driving or medical diagnosis). For models using softmax at the last layer, Temperature Scaling (TS) is a state-of-the-art calibration method, with low time and memory complexity as well as demonstrated effectiveness.TS relies on a T parameter to rescale and calibrate values of the softmax layer, using a labelled dataset to determine the value of that parameter.We are proposing an Unsupervised Temperature Scaling (UTS) approach, which does not dependent on labelled samples to calibrate the model,allowing, for example, using a part of test samples for calibrating the pre-trained model before going into inference mode. We provide theoretical justifications for UTS and assess its effectiveness on the wide range of deep models and datasets. We also demonstrate calibration results of UTS on skin lesion detection, a problem where a well-calibrated output can play an important role for accurate decision-making.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00174](http://arxiv.org/abs/1905.00174)

##### PDF
[http://arxiv.org/pdf/1905.00174](http://arxiv.org/pdf/1905.00174)

