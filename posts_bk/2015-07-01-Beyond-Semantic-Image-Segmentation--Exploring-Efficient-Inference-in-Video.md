---
layout: post
title: "Beyond Semantic Image Segmentation : Exploring Efficient Inference in Video"
date: 2015-07-01 08:06:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference
author: Subarna Tripathi, Serge Belongie, Truong Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the efficiency of the CRF inference module beyond image level semantic segmentation. The key idea is to combine the best of two worlds of semantic co-labeling and exploiting more expressive models. Similar to [Alvarez14] our formulation enables us perform inference over ten thousand images within seconds. On the other hand, it can handle higher-order clique potentials similar to [vineet2014] in terms of region-level label consistency and context in terms of co-occurrences. We follow the mean-field updates for higher order potentials similar to [vineet2014] and extend the spatial smoothness and appearance kernels [DenseCRF13] to address video data inspired by [Alvarez14]; thus making the system amenable to perform video semantic segmentation most effectively.

##### Abstract (translated by Google)
我们探索CRF​​推理模块超越图像级语义分割的效率。关键的想法是结合语义共同标注的两个世界中最好的一个，并利用更多的表达模型。与[Alvarez14]类似，我们的配方使我们能够在数秒内完成一万个图像的推断。另一方面，它可以处理类似[vineet2014]的地区级别标签一致性和上下文关于共现的高阶集团潜力。我们遵循类似于[vineet2014]的高阶势的平均场更新，并扩展空间平滑度和外观内核[DenseCRF13]，以解决由[Alvarez14]启发的视频数据。从而使系统能够最有效地进行视频语义分割。

##### URL
[https://arxiv.org/abs/1507.01578](https://arxiv.org/abs/1507.01578)

##### PDF
[https://arxiv.org/pdf/1507.01578](https://arxiv.org/pdf/1507.01578)

