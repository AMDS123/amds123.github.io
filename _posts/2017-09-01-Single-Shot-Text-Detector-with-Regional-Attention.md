---
layout: post
title: "Single Shot Text Detector with Regional Attention"
date: 2017-09-01 02:42:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention CNN Inference Prediction Detection
author: Pan He, Weilin Huang, Tong He, Qile Zhu, Yu Qiao, Xiaolin Li
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel single-shot text detector that directly outputs word-level bounding boxes in a natural image. We propose an attention mechanism which roughly identifies text regions via an automatically learned attentional map. This substantially suppresses background interference in the convolutional features, which is the key to producing accurate inference of words, particularly at extremely small sizes. This results in a single model that essentially works in a coarse-to-fine manner. It departs from recent FCN- based text detectors which cascade multiple FCN models to achieve an accurate prediction. Furthermore, we develop a hierarchical inception module which efficiently aggregates multi-scale inception features. This enhances local details, and also encodes strong context information, allow- ing the detector to work reliably on multi-scale and multi- orientation text with single-scale images. Our text detector achieves an F-measure of 77% on the ICDAR 2015 bench- mark, advancing the state-of-the-art results in [18, 28]. Demo is available at: this http URL

##### Abstract (translated by Google)
我们提出了一种新颖的单次文本检测器，直接输出自然图像中的字级边界框。我们提出了一个注意机制，通过自动学习的注意地图粗略识别文本区域。这基本上抑制了卷积特征中的背景干扰，这是产生精确推论的关键，特别是在极小的尺寸下。这导致了一个基本上以粗到细的方式工作的单一模型。它不同于最近基于FCN的文本检测器，它们级联多个FCN模型以实现准确的预测。此外，我们开发了一个等级初始模块，有效地聚合了多尺度的初始特征。这增强了局部细节，还编码了强大的上下文信息，允许探测器在单尺度图像上以多尺度和多方向文本可靠地工作。我们的文本检测器在ICDAR 2015的基准上达到了77％的F-measure，提高了最新的结果[18,28]。演示可在这个http URL

##### URL
[https://arxiv.org/abs/1709.00138](https://arxiv.org/abs/1709.00138)

##### PDF
[https://arxiv.org/pdf/1709.00138](https://arxiv.org/pdf/1709.00138)

