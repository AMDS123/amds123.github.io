---
layout: post
title: "HyperNet: Towards Accurate Region Proposal Generation and Joint Object Detection"
date: 2016-04-03 06:52:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Tao Kong, Anbang Yao, Yurong Chen, Fuchun Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Almost all of the current top-performing object detection networks employ region proposals to guide the search for object instances. State-of-the-art region proposal methods usually need several thousand proposals to get high recall, thus hurting the detection efficiency. Although the latest Region Proposal Network method gets promising detection accuracy with several hundred proposals, it still struggles in small-size object detection and precise localization (e.g., large IoU thresholds), mainly due to the coarseness of its feature maps. In this paper, we present a deep hierarchical network, namely HyperNet, for handling region proposal generation and object detection jointly. Our HyperNet is primarily based on an elaborately designed Hyper Feature which aggregates hierarchical feature maps first and then compresses them into a uniform space. The Hyper Features well incorporate deep but highly semantic, intermediate but really complementary, and shallow but naturally high-resolution features of the image, thus enabling us to construct HyperNet by sharing them both in generating proposals and detecting objects via an end-to-end joint training strategy. For the deep VGG16 model, our method achieves completely leading recall and state-of-the-art object detection accuracy on PASCAL VOC 2007 and 2012 using only 100 proposals per image. It runs with a speed of 5 fps (including all steps) on a GPU, thus having the potential for real-time processing.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1604.00600](https://arxiv.org/abs/1604.00600)

##### PDF
[https://arxiv.org/pdf/1604.00600](https://arxiv.org/pdf/1604.00600)

