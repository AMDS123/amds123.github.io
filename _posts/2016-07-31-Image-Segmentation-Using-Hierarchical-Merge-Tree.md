---
layout: post
title: "Image Segmentation Using Hierarchical Merge Tree"
date: 2016-07-31 22:14:45
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Ting Liu, Mojtaba Seyedhosseini, Tolga Tasdizen
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates one of the most fundamental computer vision problems: image segmentation. We propose a supervised hierarchical approach to object-independent image segmentation. Starting with over-segmenting superpixels, we use a tree structure to represent the hierarchy of region merging, by which we reduce the problem of segmenting image regions to finding a set of label assignment to tree nodes. We formulate the tree structure as a constrained conditional model to associate region merging with likelihoods predicted using an ensemble boundary classifier. Final segmentations can then be inferred by finding globally optimal solutions to the model efficiently. We also present an iterative training and testing algorithm that generates various tree structures and combines them to emphasize accurate boundaries by segmentation accumulation. Experiment results and comparisons with other very recent methods on six public data sets demonstrate that our approach achieves the state-of-the-art region accuracy and is very competitive in image segmentation without semantic priors.

##### Abstract (translated by Google)
本文研究了最基本的计算机视觉问题之一：图像分割。我们提出了一个监督分层的方法来独立于对象的图像分割。从超像素超分割开始，我们使用树结构来表示区域合并的层次结构，从而减少了分割图像区域的问题，找到一组树结点的标签分配问题。我们将树结构制定为受约束的条件模型，以将区域合并与使用集成边界分类器预测的可能性相关联。最终的分段可以通过有效地找到模型的全局最优解来推断。我们还提出了一种迭代训练和测试算法，生成各种树结构，并结合它们以强调分割积累的准确边界。实验结果和其他六个公共数据集上最近的其他方法的比较表明，我们的方法达到了最先进的区域准确性，并且在没有语义先验的图像分割中是非常有竞争力的。

##### URL
[https://arxiv.org/abs/1505.06389](https://arxiv.org/abs/1505.06389)

##### PDF
[https://arxiv.org/pdf/1505.06389](https://arxiv.org/pdf/1505.06389)

