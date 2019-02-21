---
layout: post
title: "Augmentation for small object detection"
date: 2019-02-19 21:47:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Mate Kisantal, Zbigniew Wojna, Jakub Murawski, Jacek Naruniec, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, object detection has experienced impressive progress. Despite these improvements, there is still a significant gap in the performance between the detection of small and large objects. We analyze the current state-of-the-art model, Mask-RCNN, on a challenging dataset, MS COCO. We show that the overlap between small ground-truth objects and the predicted anchors is much lower than the expected IoU threshold. We conjecture this is due to two factors; (1) only a few images are containing small objects, and (2) small objects do not appear enough even within each image containing them. We thus propose to oversample those images with small objects and augment each of those images by copy-pasting small objects many times. It allows us to trade off the quality of the detector on large objects with that on small objects. We evaluate different pasting augmentation strategies, and ultimately, we achieve 9.7\% relative improvement on the instance segmentation and 7.1\% on the object detection of small objects, compared to the current state of the art method on MS COCO.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07296](http://arxiv.org/abs/1902.07296)

##### PDF
[http://arxiv.org/pdf/1902.07296](http://arxiv.org/pdf/1902.07296)

