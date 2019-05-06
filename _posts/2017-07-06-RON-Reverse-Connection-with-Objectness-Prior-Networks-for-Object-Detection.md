---
layout: post
title: "RON: Reverse Connection with Objectness Prior Networks for Object Detection"
date: 2017-07-06 08:53:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Tao Kong, Fuchun Sun, Anbang Yao, Huaping Liu, Ming Lu, Yurong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We present RON, an efficient and effective framework for generic object detection. Our motivation is to smartly associate the best of the region-based (e.g., Faster R-CNN) and region-free (e.g., SSD) methodologies. Under fully convolutional architecture, RON mainly focuses on two fundamental problems: (a) multi-scale object localization and (b) negative sample mining. To address (a), we design the reverse connection, which enables the network to detect objects on multi-levels of CNNs. To deal with (b), we propose the objectness prior to significantly reduce the searching space of objects. We optimize the reverse connection, objectness prior and object detector jointly by a multi-task loss function, thus RON can directly predict final detection results from all locations of various feature maps. Extensive experiments on the challenging PASCAL VOC 2007, PASCAL VOC 2012 and MS COCO benchmarks demonstrate the competitive performance of RON. Specifically, with VGG-16 and low resolution 384X384 input size, the network gets 81.3% mAP on PASCAL VOC 2007, 80.7% mAP on PASCAL VOC 2012 datasets. Its superiority increases when datasets become larger and more difficult, as demonstrated by the results on the MS COCO dataset. With 1.5G GPU memory at test phase, the speed of the network is 15 FPS, 3X faster than the Faster R-CNN counterpart.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.01691](https://arxiv.org/abs/1707.01691)

##### PDF
[https://arxiv.org/pdf/1707.01691](https://arxiv.org/pdf/1707.01691)

