---
layout: post
title: "Pedestrian Detection with Autoregressive Network Phases"
date: 2018-12-02 18:18:22
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Garrick Brazil, Xiaoming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We present an autoregressive pedestrian detection framework with cascaded phases designed to progressively improve precision. The proposed framework utilizes a novel lightweight stackable decoder-encoder module which uses convolutional re-sampling layers to improve features while maintaining efficient memory and runtime cost. Unlike previous cascaded detection systems, our proposed framework is designed within a region proposal network and thus retains greater context of nearby detections compared to independently processed RoI systems. We explicitly encourage increasing levels of precision by assigning strict labeling policies to each consecutive phase such that early phases develop features primarily focused on achieving high recall and later on accurate precision. In consequence, the final feature maps form more peaky radial gradients emulating from the centroids of unique pedestrians. Using our proposed autoregressive framework leads to new state-of-the-art performance on the reasonable and occlusion settings of the Caltech pedestrian dataset, and achieves competitive state-of-the-art performance on the KITTI dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00440](http://arxiv.org/abs/1812.00440)

##### PDF
[http://arxiv.org/pdf/1812.00440](http://arxiv.org/pdf/1812.00440)

