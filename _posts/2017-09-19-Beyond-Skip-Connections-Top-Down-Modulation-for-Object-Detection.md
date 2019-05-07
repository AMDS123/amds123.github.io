---
layout: post
title: "Beyond Skip Connections: Top-Down Modulation for Object Detection"
date: 2017-09-19 22:37:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Abhinav Shrivastava, Rahul Sukthankar, Jitendra Malik, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, we have seen tremendous progress in the field of object detection. Most of the recent improvements have been achieved by targeting deeper feedforward networks. However, many hard object categories such as bottle, remote, etc. require representation of fine details and not just coarse, semantic representations. But most of these fine details are lost in the early convolutional layers. What we need is a way to incorporate finer details from lower layers into the detection architecture. Skip connections have been proposed to combine high-level and low-level features, but we argue that selecting the right features from low-level requires top-down contextual information. Inspired by the human visual pathway, in this paper we propose top-down modulations as a way to incorporate fine details into the detection framework. Our approach supplements the standard bottom-up, feedforward ConvNet with a top-down modulation (TDM) network, connected using lateral connections. These connections are responsible for the modulation of lower layer filters, and the top-down network handles the selection and integration of contextual information and low-level features. The proposed TDM architecture provides a significant boost on the COCO testdev benchmark, achieving 28.6 AP for VGG16, 35.2 AP for ResNet101, and 37.3 for InceptionResNetv2 network, without any bells and whistles (e.g., multi-scale, iterative box refinement, etc.).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1612.06851](https://arxiv.org/abs/1612.06851)

##### PDF
[https://arxiv.org/pdf/1612.06851](https://arxiv.org/pdf/1612.06851)

