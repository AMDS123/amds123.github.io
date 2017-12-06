---
layout: post
title: "Revisiting Graph Construction for Fast Image Segmentation"
date: 2017-12-02 22:40:39
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Zizhao Zhang, Fuyong Xing, Hanzi Wang, Yan Yan, Ying Huang, Xiaoshuang Shi, Lin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a simple but effective method for fast image segmentation. We re-examine the locality-preserving character of spectral clustering by constructing a graph over image regions with both global and local connections. Our novel approach to build graph connections relies on two key observations: 1) local region pairs that co-occur frequently will have a high probability to reside on a common object; 2) spatially distant regions in a common object often exhibit similar visual saliency, which implies their neighborship in a manifold. We present a novel energy function to efficiently conduct graph partitioning. Based on multiple high quality partitions, we show that the generated eigenvector histogram based representation can automatically drive effective unary potentials for a hierarchical random field model to produce multi-class segmentation. Sufficient experiments, on the BSDS500 benchmark, large-scale PASCAL VOC and COCO datasets, demonstrate the competitive segmentation accuracy and significantly improved efficiency of our proposed method compared with other state of the arts.

##### Abstract (translated by Google)
在本文中，我们提出了一个简单而有效的快速图像分割方法。我们通过在全局和局部连接的图像区域上构建一个图来重新检查谱聚类的局部保持特性。我们建立图连接的新方法依赖于两个关键的观察：1）经常出现的局部区域对将很有可能驻留在一个共同的对象上; 2）在一个共同的对象空间遥远的地区往往表现出相似的视觉显着性，这意味着他们的邻居在一个歧管。我们提出了一种新的能量函数来有效地进行图分区。基于多个高质量分区，我们证明了生成的基于特征向量直方图的表示可以自动驱动一个分层随机场模型的有效一元电位来产生多类分割。在BSDS500基准，大型PASCAL VOC和COCO数据集上进行充分的实验证明了与其他国家相比，我们所提出方法的竞争性分割准确性和显着提高的效率。

##### URL
[http://arxiv.org/abs/1702.05650](http://arxiv.org/abs/1702.05650)

