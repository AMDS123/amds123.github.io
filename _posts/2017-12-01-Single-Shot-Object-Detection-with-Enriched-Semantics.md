---
layout: post
title: "Single-Shot Object Detection with Enriched Semantics"
date: 2017-12-01 18:18:42
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Detection
author: Zhishuai Zhang, Siyuan Qiao, Cihang Xie, Wei Shen, Bo Wang, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel single shot object detection network named Detection with Enriched Semantics (DES). Our motivation is to enrich the semantics of object detection features within a typical deep detector, by a semantic segmentation branch and a location-agnostic module. The segmentation branch is supervised by weak segmentation ground-truth, i.e., no extra annotation is required. In conjunction with that, we employ a location-agnostic module which learns relationship between channels and object classes in a self-supervised manner. Comprehensive experimental results on both PASCAL VOC and MS COCO detection datasets demonstrate the effectiveness of the proposed method. In particular, with a VGG16 based DES, we achieve an mAP of 81.6 on VOC2007 test and an mmAP of 32.8 on COCO test-dev with an inference speed of 36.7 milliseconds per image on a Titan X Pascal GPU. With a lower resolution version, we achieve an mAP of 79.5 on VOC2007 with an inference speed of 14.7 milliseconds per image.

##### Abstract (translated by Google)
我们提出了一种新颖的单次物体检测网络，名为Detection with Enriched Semantics（DES）。我们的动机是丰富典型的深度检测器内的物体检测特征的语义，通过语义分割分支和位置不可知模块。分割分支由弱分割地面真值监督，即不需要额外的注释。结合这一点，我们使用一个位置不可知的模块，以自我监督的方式学习渠道和对象类之间的关系。在PASCAL VOC和MS COCO检测数据集上的综合实验结果证明了所提出的方法的有效性。特别是在基于VGG16的DES中，我们实现了VOC2007测试的mAP为81.6，COCO test-dev为32.8，在Titan X Pascal GPU上的图像推理速度为36.7毫秒。使用较低分辨率的版本，我们在VOC2007上实现了79.5的mAP，推断速度为每个图像14.7毫秒。

##### URL
[https://arxiv.org/abs/1712.00433](https://arxiv.org/abs/1712.00433)

##### PDF
[https://arxiv.org/pdf/1712.00433](https://arxiv.org/pdf/1712.00433)

