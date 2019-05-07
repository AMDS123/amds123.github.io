---
layout: post
title: "Crafting GBD-Net for Object Detection"
date: 2016-10-08 20:36:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Relation
author: Xingyu Zeng, Wanli Ouyang, Junjie Yan, Hongsheng Li, Tong Xiao, Kun Wang, Yu Liu, Yucong Zhou, Bin Yang, Zhe Wang, Hui Zhou, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The visual cues from multiple support regions of different sizes and resolutions are complementary in classifying a candidate box in object detection. Effective integration of local and contextual visual cues from these regions has become a fundamental problem in object detection. In this paper, we propose a gated bi-directional CNN (GBD-Net) to pass messages among features from different support regions during both feature learning and feature extraction. Such message passing can be implemented through convolution between neighboring support regions in two directions and can be conducted in various layers. Therefore, local and contextual visual patterns can validate the existence of each other by learning their nonlinear relationships and their close interactions are modeled in a more complex way. It is also shown that message passing is not always helpful but dependent on individual samples. Gated functions are therefore needed to control message transmission, whose on-or-offs are controlled by extra visual evidence from the input sample. The effectiveness of GBD-Net is shown through experiments on three object detection datasets, ImageNet, Pascal VOC2007 and Microsoft COCO. This paper also shows the details of our approach in wining the ImageNet object detection challenge of 2016, with source code provided on \url{this https URL}.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1610.02579](https://arxiv.org/abs/1610.02579)

##### PDF
[https://arxiv.org/pdf/1610.02579](https://arxiv.org/pdf/1610.02579)

