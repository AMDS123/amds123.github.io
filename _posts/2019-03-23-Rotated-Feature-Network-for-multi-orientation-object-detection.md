---
layout: post
title: "Rotated Feature Network for multi-orientation object detection"
date: 2019-03-23 16:10:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Quantitative Detection
author: Zhixin Zhang, Xudong Chen, Jie Lie, Kaibo Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
General detectors follow the pipeline that feature maps extracted from ConvNets are shared between classification and regression tasks. However, there exists obvious conflicting requirements in multi-orientation object detection that classification is insensitive to orientations, while regression is quite sensitive. To address this issue, we provide an Encoder-Decoder architecture, called Rotated Feature Network (RFN), which produces rotation-sensitive feature maps (RS) for regression and rotation-invariant feature maps (RI) for classification. Specifically, the Encoder unit assigns weights for rotated feature maps. The Decoder unit extracts RS and RI by performing resuming operator on rotated and reweighed feature maps, respectively. To make the rotation-invariant characteristics more reliable, we adopt a metric to quantitatively evaluate the rotation-invariance by adding a constrain item in the loss, yielding a promising detection performance. Compared with the state-of-the-art methods, our method can achieve significant improvement on NWPU VHR-10 and RSOD datasets. We further evaluate the RFN on the scene classification in remote sensing images and object detection in natural images, demonstrating its good generalization ability. The proposed RFN can be integrated into an existing framework, leading to great performance with only a slight increase in model complexity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09839](http://arxiv.org/abs/1903.09839)

##### PDF
[http://arxiv.org/pdf/1903.09839](http://arxiv.org/pdf/1903.09839)

