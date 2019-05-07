---
layout: post
title: "Object Detection in Videos with Tubelet Proposal Networks"
date: 2017-04-10 08:39:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Tracking Object_Tracking RNN Detection
author: Kai Kang, Hongsheng Li, Tong Xiao, Wanli Ouyang, Junjie Yan, Xihui Liu, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection in videos has drawn increasing attention recently with the introduction of the large-scale ImageNet VID dataset. Different from object detection in static images, temporal information in videos is vital for object detection. To fully utilize temporal information, state-of-the-art methods are based on spatiotemporal tubelets, which are essentially sequences of associated bounding boxes across time. However, the existing methods have major limitations in generating tubelets in terms of quality and efficiency. Motion-based methods are able to obtain dense tubelets efficiently, but the lengths are generally only several frames, which is not optimal for incorporating long-term temporal information. Appearance-based methods, usually involving generic object tracking, could generate long tubelets, but are usually computationally expensive. In this work, we propose a framework for object detection in videos, which consists of a novel tubelet proposal network to efficiently generate spatiotemporal proposals, and a Long Short-term Memory (LSTM) network that incorporates temporal information from tubelet proposals for achieving high object detection accuracy in videos. Experiments on the large-scale ImageNet VID dataset demonstrate the effectiveness of the proposed framework for object detection in videos.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1702.06355](https://arxiv.org/abs/1702.06355)

##### PDF
[https://arxiv.org/pdf/1702.06355](https://arxiv.org/pdf/1702.06355)

