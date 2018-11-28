---
layout: post
title: "Fast Object Detection in Compressed Video"
date: 2018-11-27 15:35:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Attention CNN Deep_Learning Prediction Detection
author: Shiyao Wang, Hongchao Lu, Pavel Dmitriev, Zhidong Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection in videos has drawn increasing attention recently since it is more important in real scenarios. Most of the deep learning methods for video analysis use convolutional neural networks designed for image-wise parsing in a video stream. But they usually ignore the fact that a video is generally stored and transmitted in a compressed data format. In this paper, we propose a fast object detection model that incorporates light-weight motion-aided memory network (MMNet), which can be directly used for H.264 compressed video. MMNet has two major advantages: 1) For a group of successive pictures (GOP) in a compressed video stream, it runs the heavy computational network for I-frames, i.e. a few reference frames in videos, while a light-weight memory network is designed to generate features for prediction frames called P-frames; 2) Unlike establishing an additional network to explicitly model motion among frames, we directly take full advantage of both motion vectors and residual errors that are all encoded in a compressed video. Such signals maintain spatial variations and are freely available. To our best knowledge, the MMNet is the first work that explores a convolutional detector on a compressed video and a motion-based memory in order to achieve significant speedup. Our model is evaluated on the large-scale ImageNet VID dataset, and the results show that it is about 3x times faster than single image detector R-FCN and 10x times faster than high performance detectors like FGFA and MANet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11057](http://arxiv.org/abs/1811.11057)

##### PDF
[http://arxiv.org/pdf/1811.11057](http://arxiv.org/pdf/1811.11057)

