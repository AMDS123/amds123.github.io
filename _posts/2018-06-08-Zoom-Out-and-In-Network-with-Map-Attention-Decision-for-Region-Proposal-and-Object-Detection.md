---
layout: post
title: "Zoom Out-and-In Network with Map Attention Decision for Region Proposal and Object Detection"
date: 2018-06-08 09:59:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention CNN Detection
author: Hongyang Li, Yu Liu, Wanli Ouyang, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a zoom-out-and-in network for generating object proposals. A key observation is that it is difficult to classify anchors of different sizes with the same set of features. Anchors of different sizes should be placed accordingly based on different depth within a network: smaller boxes on high-resolution layers with a smaller stride while larger boxes on low-resolution counterparts with a larger stride. Inspired by the conv/deconv structure, we fully leverage the low-level local details and high-level regional semantics from two feature map streams, which are complimentary to each other, to identify the objectness in an image. A map attention decision (MAD) unit is further proposed to aggressively search for neuron activations among two streams and attend the most contributive ones on the feature learning of the final loss. The unit serves as a decisionmaker to adaptively activate maps along certain channels with the solely purpose of optimizing the overall training loss. One advantage of MAD is that the learned weights enforced on each feature channel is predicted on-the-fly based on the input context, which is more suitable than the fixed enforcement of a convolutional kernel. Experimental results on three datasets, including PASCAL VOC 2007, ImageNet DET, MS COCO, demonstrate the effectiveness of our proposed algorithm over other state-of-the-arts, in terms of average recall (AR) for region proposal and average precision (AP) for object detection.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1709.04347](https://arxiv.org/abs/1709.04347)

##### PDF
[https://arxiv.org/pdf/1709.04347](https://arxiv.org/pdf/1709.04347)

