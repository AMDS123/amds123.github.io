---
layout: post
title: "DiCENet: Dimension-wise Convolutions for Efficient Networks"
date: 2019-06-08 20:17:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation NAS Image_Classification Semantic_Segmentation Classification Detection Recognition
author: Sachin Mehta, Hannaneh Hajishirzi, Mohammad Rastegari
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new CNN model DiCENet, that is built using: (1) dimension-wise convolutions and (2) efficient channel fusion. The introduced blocks maximize the use of information in the input tensor by learning representations across all dimensions while simultaneously reducing the complexity of the network and achieving high accuracy. Our model shows significant improvements over state-of-the-art models across various visual recognition tasks, including image classification, object detection, and semantic segmentation. Our model delivers either the same or better performance than existing models with fewer FLOPs, including task-specific models. Notably, DiCENet delivers competitive performance to neural architecture search-based methods at fewer FLOPs (70-100 MFLOPs). On the MS-COCO object detection, DiCENet is 4.5% more accurate and has 5.6 times fewer FLOPs than YOLOv2. On the PASCAL VOC 2012 semantic segmentation dataset, DiCENet is 4.3% more accurate and has 3.2 times fewer FLOPs than a recent efficient semantic segmentation network, ESPNet. Our source code is available at \url{https://github.com/sacmehta/EdgeNets}

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03516](http://arxiv.org/abs/1906.03516)

##### PDF
[http://arxiv.org/pdf/1906.03516](http://arxiv.org/pdf/1906.03516)

