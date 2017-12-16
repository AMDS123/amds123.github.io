---
layout: post
title: "R2CNN: Rotational Region CNN for Orientation Robust Scene Text Detection"
date: 2017-06-30 13:01:52
categories: arXiv_CV
tags: arXiv_CV Detection
author: Yingying Jiang, Xiangyu Zhu, Xiaobing Wang, Shuli Yang, Wei Li, Hua Wang, Pei Fu, Zhenbo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel method called Rotational Region CNN (R2CNN) for detecting arbitrary-oriented texts in natural scene images. The framework is based on Faster R-CNN [1] architecture. First, we use the Region Proposal Network (RPN) to generate axis-aligned bounding boxes that enclose the texts with different orientations. Second, for each axis-aligned text box proposed by RPN, we extract its pooled features with different pooled sizes and the concatenated features are used to simultaneously predict the text/non-text score, axis-aligned box and inclined minimum area box. At last, we use an inclined non-maximum suppression to get the detection results. Our approach achieves competitive results on text detection benchmarks: ICDAR 2015 and ICDAR 2013.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的旋转区域CNN（R2CNN）方法来检测自然场景图像中的任意方向的文本。该框架基于更快的R-CNN [1]架构。首先，我们使用区域提议网络（RPN）来生成轴对齐的包围不同方向的文本的边界框。其次，针对RPN提出的每个轴对齐文本框，我们提取不同合并大小的合并特征，使用连接特征同时预测文本/非文本评分，轴对齐框和倾斜最小区域框。最后，我们使用倾斜的非最大抑制来获得检测结果。我们的方法在文本检测基准方面取得了具有竞争力的成果：ICDAR 2015和ICDAR 2013。

##### URL
[https://arxiv.org/abs/1706.09579](https://arxiv.org/abs/1706.09579)

##### PDF
[https://arxiv.org/pdf/1706.09579](https://arxiv.org/pdf/1706.09579)

