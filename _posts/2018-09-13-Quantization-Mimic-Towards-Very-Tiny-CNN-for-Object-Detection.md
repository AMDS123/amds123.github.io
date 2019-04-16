---
layout: post
title: "Quantization Mimic: Towards Very Tiny CNN for Object Detection"
date: 2018-09-13 09:03:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Face Detection
author: Yi Wei, Xinyu Pan, Hongwei Qin, Wanli Ouyang, Junjie Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a simple and general framework for training very tiny CNNs for object detection. Due to limited representation ability, it is challenging to train very tiny networks for complicated tasks like detection. To the best of our knowledge, our method, called Quantization Mimic, is the first one focusing on very tiny networks. We utilize two types of acceleration methods: mimic and quantization. Mimic improves the performance of a student network by transfering knowledge from a teacher network. Quantization converts a full-precision network to a quantized one without large degradation of performance. If the teacher network is quantized, the search scope of the student network will be smaller. Using this feature of the quantization, we propose Quantization Mimic. It first quantizes the large network, then mimic a quantized small network. The quantization operation can help student network to better match the feature maps from teacher network. To evaluate our approach, we carry out experiments on various popular CNNs including VGG and Resnet, as well as different detection frameworks including Faster R-CNN and R-FCN. Experiments on Pascal VOC and WIDER FACE verify that our Quantization Mimic algorithm can be applied on various settings and outperforms state-of-the-art model acceleration methods given limited computing resouces.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.02152](https://arxiv.org/abs/1805.02152)

##### PDF
[https://arxiv.org/pdf/1805.02152](https://arxiv.org/pdf/1805.02152)

