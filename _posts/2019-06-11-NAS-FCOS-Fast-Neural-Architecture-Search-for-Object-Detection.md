---
layout: post
title: "NAS-FCOS: Fast Neural Architecture Search for Object Detection"
date: 2019-06-11 07:55:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection NAS Reinforcement_Learning Prediction Detection
author: Ning Wang, Yang Gao, Hao Chen, Peng Wang, Zhi Tian, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
The success of deep neural networks relies on significant architecture engineering. Recently neural architecture search (NAS) has emerged as a promise to greatly reduce manual effort in network design by automatically searching for optimal architectures, although typically such algorithms need an excessive amount of computational resources, e.g., a few thousand GPU-days. To date, on challenging vision tasks such as object detection, NAS, especially fast versions of NAS, is less studied. Here we propose to search for the decoder structure of object detectors with search efficiency being taken into consideration. To be more specific, we aim to efficiently search for the feature pyramid network (FPN) as well as the prediction head of a simple anchor-free object detector, namely FCOS [20], using a tailored reinforcement learning paradigm. With carefully designed search space, search algorithms and strategies for evaluating network quality, we are able to efficiently search more than 2, 000 architectures in around 30 GPU-days. The discovered architecture surpasses state-of-the-art object detection models (such as Faster R-CNN, RetinaNet and FCOS) by 1 to 1.9 points in AP on the COCO dataset, with comparable computation complexity and memory footprint, demonstrating the efficacy of the proposed NAS for object detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04423](http://arxiv.org/abs/1906.04423)

##### PDF
[http://arxiv.org/pdf/1906.04423](http://arxiv.org/pdf/1906.04423)

