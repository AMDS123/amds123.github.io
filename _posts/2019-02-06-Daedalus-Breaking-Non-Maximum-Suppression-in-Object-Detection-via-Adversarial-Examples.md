---
layout: post
title: "Daedalus: Breaking Non-Maximum Suppression in Object Detection via Adversarial Examples"
date: 2019-02-06 08:58:37
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection CNN Detection
author: Derui Wang, Chaoran Li, Sheng Wen, Surya Nepal, Yang Xiang
mathjax: true
---

* content
{:toc}

##### Abstract
We demonstrated that Non-Maximum Suppression (NMS), which is commonly used in object detection tasks to filter redundant detection results, is no longer secure. NMS has always been an integral part of object detection algorithms. Currently, Fully Convolutional Network (FCN) is widely used as the backbone architecture of object detection models. Given an input instance, since FCN generates end-to-end detection results in a single stage, it outputs a large number of raw detection boxes. These bounding boxes are then filtered by NMS to make the final detection results. 
 In this paper, we propose an adversarial example attack which triggers malfunctioning of NMS in the end-to-end object detection models. Our attack, namely Daedalus, manipulates the detection box regression values to compress the dimensions of detection boxes. Henceforth, NMS will no longer be able to filter redundant detection boxes correctly. And as a result, the final detection output contains extremely dense false positives. This can be fatal for many object detection applications such as autonomous vehicle and smart manufacturing industry. Our attack can be applied to different end-to-end object detection models. Furthermore, we suggest crafting robust adversarial examples by using an ensemble of popular detection models as the substitutes. Considering that model reusing is commonly seen in real-world object detection scenarios, Daedalus examples crafted based on an ensemble of substitutes can launch attacks without knowing the details of the victim models. Our experiments demonstrate that our attack effectively stops NMS from filtering redundant bounding boxes. As the evaluation results suggest, Daedalus increases the false positive rate in detection results to 99.9% and reduces the mean average precision scores to 0, while maintaining a low cost of distortion on the original inputs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02067](http://arxiv.org/abs/1902.02067)

##### PDF
[http://arxiv.org/pdf/1902.02067](http://arxiv.org/pdf/1902.02067)

