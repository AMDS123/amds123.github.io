---
layout: post
title: "Interferences in match kernels"
date: 2016-11-24 14:25:43
categories: arXiv_CV
tags: arXiv_CV Image_Caption Image_Retrieval OCR
author: Naila Murray, Hervé Jégou, Florent Perronnin, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the design of an image representation that embeds and aggregates a set of local descriptors into a single vector. Popular representations of this kind include the bag-of-visual-words, the Fisher vector and the VLAD. When two such image representations are compared with the dot-product, the image-to-image similarity can be interpreted as a match kernel. In match kernels, one has to deal with interference, i.e. with the fact that even if two descriptors are unrelated, their matching score may contribute to the overall similarity. We formalise this problem and propose two related solutions, both aimed at equalising the individual contributions of the local descriptors in the final representation. These methods modify the aggregation stage by including a set of per-descriptor weights. They differ by the objective function that is optimised to compute those weights. The first is a "democratisation" strategy that aims at equalising the relative importance of each descriptor in the set comparison metric. The second one involves equalising the match of a single descriptor to the aggregated vector. These concurrent methods give a substantial performance boost over the state of the art in image search with short or mid-size vectors, as demonstrated by our experiments on standard public image retrieval benchmarks.

##### Abstract (translated by Google)
我们考虑一个图像表示的设计，它将一组局部描述符嵌入和聚合成一个单独的向量。这种流行的表现形式包括视觉词袋，费舍尔矢量和VLAD。当两个这样的图像表示与点积进行比较时，图像与图像之间的相似性可以被解释为匹配内核。在匹配核心中，必须处理干扰，即，即使两个描述符不相关，它们的匹配分数也可能有助于总体相似性。我们将这个问题正式化，并提出了两个相关的解决方案，都旨在均衡地方描述符在最终表示中的个人贡献。这些方法通过包含一组每个描述符权重来修改聚合阶段。他们不同的目标函数是优化来计算这些权重。第一个是“民主化”战略，旨在平衡每个描述符在集合比较度量中的相对重要性。第二个涉及到均衡单个描述符与聚合向量的匹配。这些并发方法在短中型矢量图像搜索领域比现有技术水平显着提高，正如我们在标准公共图像检索基准上的实验所证明的那样。

##### URL
[https://arxiv.org/abs/1611.08194](https://arxiv.org/abs/1611.08194)

##### PDF
[https://arxiv.org/pdf/1611.08194](https://arxiv.org/pdf/1611.08194)

