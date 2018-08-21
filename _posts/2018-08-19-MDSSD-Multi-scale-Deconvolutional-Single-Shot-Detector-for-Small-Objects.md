---
layout: post
title: "MDSSD: Multi-scale Deconvolutional Single Shot Detector for Small Objects"
date: 2018-08-19 04:59:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Prediction Detection
author: Mingliang Xu, Lisha Cui, Pei Lv, Xiaoheng Jiang, Jianwei Niu, Bing Zhou, Meng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
For most of the object detectors based on multi-scale feature maps, the shallow layers are mainly responsible for small object detection due to their fine details. However, the performance of detecting small object instances is still less satisfactory because of the deficiency of semantic information on shallow features. For the top semantic features, the representation of fine details for small objects are potentially wiped out. In this paper, we design a Multi-scale Deconvolutional Single Shot Detector (MDSSD), especially for the detection of small objects. In MDSSD, to generate features with strong representational power for small object instances, we add the high-level features with rich semantic information to the low-level features via deconvolution Fusion Block. It is noteworthy that multiple high-level features with different scales are upsampled simultaneously in our framework. Afterwards, we implement the skip connections to form more descriptive feature maps for small objects and predictions are made on these new fusion features. Our proposed framework achieves 78.6% mAP on PASCAL VOC2007 test and 26.8% mAP on MS COCO test-dev2015 at 38.5 FPS with only 300*300 input. The results outperform baseline SSD by 1.1 and 1.7 points respectively, especially with 2 -- 5 points improvement on some small objects categories.

##### Abstract (translated by Google)
对于基于多尺度特征图的大多数物体检测器，浅层主要负责小物体检测，因为它们具有精细的细节。然而，由于浅特征上的语义信息的不足，检测小对象实例的性能仍然不太令人满意。对于顶级语义特征，可能会消除小对象的精细细节的表示。在本文中，我们设计了一个多尺度反卷积单发探测器（MDSSD），特别是用于小物体的探测。在MDSSD中，为了生成具有强大的表示能力的特征，我们通过解卷积Fusion Block将具有丰富语义信息的高级特征添加到低级特征中。值得注意的是，我们的框架中同时对多个具有不同比例的高级特征进行了上采样。之后，我们实现跳过连接，为小对象形成更具描述性的特征映射，并对这些新的融合特征进行预测。我们提出的框架在PASCAL VOC2007测试中达到78.6％mAP，在MS COCO test-dev2015上以38.5 FPS达到26.8％mAP，仅输入300 * 300。结果优于基准SSD分别为1.1和1.7分，特别是在一些小对象类别上改善了2至5分。

##### URL
[http://arxiv.org/abs/1805.07009](http://arxiv.org/abs/1805.07009)

##### PDF
[http://arxiv.org/pdf/1805.07009](http://arxiv.org/pdf/1805.07009)

