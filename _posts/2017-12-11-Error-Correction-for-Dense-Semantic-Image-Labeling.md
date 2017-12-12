---
layout: post
title: "Error Correction for Dense Semantic Image Labeling"
date: 2017-12-11 15:11:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Semantic_Segmentation Optimization Inference Quantitative
author: Yu-Hui Huang, Xu Jia, Stamatios Georgoulis, Tinne Tuytelaars, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Pixelwise semantic image labeling is an important, yet challenging, task with many applications. Typical approaches to tackle this problem involve either the training of deep networks on vast amounts of images to directly infer the labels or the use of probabilistic graphical models to jointly model the dependencies of the input (i.e. images) and output (i.e. labels). Yet, the former approaches do not capture the structure of the output labels, which is crucial for the performance of dense labeling, and the latter rely on carefully hand-designed priors that require costly parameter tuning via optimization techniques, which in turn leads to long inference times. To alleviate these restrictions, we explore how to arrive at dense semantic pixel labels given both the input image and an initial estimate of the output labels. We propose a parallel architecture that: 1) exploits the context information through a LabelPropagation network to propagate correct labels from nearby pixels to improve the object boundaries, 2) uses a LabelReplacement network to directly replace possibly erroneous, initial labels with new ones, and 3) combines the different intermediate results via a Fusion network to obtain the final per-pixel label. We experimentally validate our approach on two different datasets for the semantic segmentation and face parsing tasks respectively, where we show improvements over the state-of-the-art. We also provide both a quantitative and qualitative analysis of the generated results.

##### Abstract (translated by Google)
逐像素语义图像标注是许多应用程序中重要而又具有挑战性的任务。解决这个问题的典型方法涉及在大量图像上训练深度网络以直接推断标签，或者使用概率图形模型来联合建模输入（即图像）和输出（即标签）的相关性。然而，前面的方法并没有捕捉输出标签的结构，这对于密集标签的性能是至关重要的，而后者依赖于精心设计的手工设计的先验，其需要通过优化技术进行昂贵的参数调整，这又导致长推断时间。为了减轻这些限制，我们探讨了如何在给定输入图像和输出标签的初始估计的情况下得到密集的语义像素标签。我们提出了一个并行体系结构：1）通过LabelPropagation网络利用上下文信息传播来自附近像素的正确标签以改善对象边界; 2）使用LabelReplacement网络直接用新的标签替换可能错误的初始标签; 3） ）通过融合网络结合不同的中间结果来获得最终的每像素标签。我们在两个不同的数据集上实验性地验证了我们的方法，分别用于语义分割和人脸解析任务，在这些方面我们展示了对最新技术的改进。我们还提供了生成结果的定量和定性分析。

##### URL
[http://arxiv.org/abs/1712.03812](http://arxiv.org/abs/1712.03812)

##### PDF
[http://arxiv.org/pdf/1712.03812](http://arxiv.org/pdf/1712.03812)

