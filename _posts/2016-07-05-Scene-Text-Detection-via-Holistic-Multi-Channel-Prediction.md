---
layout: post
title: "Scene Text Detection via Holistic, Multi-Channel Prediction"
date: 2016-07-05 11:22:49
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction Detection Relation
author: Cong Yao, Xiang Bai, Nong Sang, Xinyu Zhou, Shuchang Zhou, Zhimin Cao
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, scene text detection has become an active research topic in computer vision and document analysis, because of its great importance and significant challenge. However, vast majority of the existing methods detect text within local regions, typically through extracting character, word or line level candidates followed by candidate aggregation and false positive elimination, which potentially exclude the effect of wide-scope and long-range contextual cues in the scene. To take full advantage of the rich information available in the whole natural image, we propose to localize text in a holistic manner, by casting scene text detection as a semantic segmentation problem. The proposed algorithm directly runs on full images and produces global, pixel-wise prediction maps, in which detections are subsequently formed. To better make use of the properties of text, three types of information regarding text region, individual characters and their relationship are estimated, with a single Fully Convolutional Network (FCN) model. With such predictions of text properties, the proposed algorithm can simultaneously handle horizontal, multi-oriented and curved text in real-world natural images. The experiments on standard benchmarks, including ICDAR 2013, ICDAR 2015 and MSRA-TD500, demonstrate that the proposed algorithm substantially outperforms previous state-of-the-art approaches. Moreover, we report the first baseline result on the recently-released, large-scale dataset COCO-Text.

##### Abstract (translated by Google)
近年来，场景文本检测已经成为计算机视觉和文档分析的一个活跃的研究课题，因为它具有重要的意义和重大的挑战。然而，绝大多数现有的方法通常是通过提取字符，单词或行级候选，然后是候选聚合和假阳性消除来检测局部区域内的文本，这潜在地排除了宽范围和远程上下文线索在现场。为了充分利用整个自然图像中丰富的信息，我们建议整体定位文本，将场景文本检测作为语义分割问题。所提出的算法直接在全图像上运行，并产生全局的，逐像素的预测图，其中检测随后形成。为了更好地利用文本的属性，使用单一的全卷积网络（FCN）模型来估计关于文本区域，单个字符及其关系的三种类型的信息。通过对文本属性的这种预测，所提出的算法能够同时处理真实世界中自然图像中的水平，多向和曲线文本。包括ICDAR 2013，ICDAR 2015和MSRA-TD500在内的标准基准的实验表明，所提出的算法大大优于先前的最新方法。此外，我们在最近发布的大型数据集COCO-Text上报告了第一个基线结果。

##### URL
[https://arxiv.org/abs/1606.09002](https://arxiv.org/abs/1606.09002)

##### PDF
[https://arxiv.org/pdf/1606.09002](https://arxiv.org/pdf/1606.09002)

