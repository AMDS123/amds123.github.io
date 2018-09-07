---
layout: post
title: "Towards Interpretable R-CNN by Unfolding Latent Structures"
date: 2018-09-06 16:52:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Tianfu Wu, Wei Sun, Xilai Li, Xi Song, Bo Li
mathjax: true
---

* content
{:toc}

##### Abstract
This paper first proposes a method of formulating model interpretability in visual understanding tasks based on the idea of unfolding latent structures. It then presents a case study in object detection using popular two-stage region-based convolutional network (i.e., R-CNN) detection systems. We focus on weakly-supervised extractive rationale generation, that is learning to unfold latent discriminative part configurations of object instances automatically and simultaneously in detection without using any supervision for part configurations. We utilize a top-down hierarchical and compositional grammar model embedded in a directed acyclic AND-OR Graph (AOG) to explore and unfold the space of latent part configurations of regions of interest (RoIs). We propose an AOGParsing operator to substitute the RoIPooling operator widely used in R-CNN. In detection, a bounding box is interpreted by the best parse tree derived from the AOG on-the-fly, which is treated as the qualitatively extractive rationale generated for interpreting detection. We propose a folding-unfolding method to train the AOG and convolutional networks end-to-end. In experiments, we build on R-FCN and test our method on the PASCAL VOC 2007 and 2012 datasets. We show that the method can unfold promising latent structures without hurting the performance.

##### Abstract (translated by Google)
本文首先提出了一种基于展开潜在结构的思想，在视觉理解任务中制定模型可解释性的方法。然后，它提出了使用流行的基于两阶段区域的卷积网络（即R-CNN）检测系统进行物体检测的案例研究。我们专注于弱监督的提取原理生成，即学习在检测中自动和同时展开对象实例的潜在判别部分配置，而不使用任何部件配置监督。我们利用嵌入在有向无环AND-OR图（AOG）中的自上而下的分层和组合语法模型来探索和展开感兴趣区域（RoI）的潜在部分配置的空间。我们提出了一个AOGParsing运算符来代替广泛用于R-CNN的RoIPooling运算符。在检测中，边界框由在动态上从AOG导出的最佳解析树解释，其被视为为解释检测而生成的定性提取原理。我们提出了一种折叠展开方法来端对端地训练AOG和卷积网络。在实验中，我们在R-FCN上构建并在PASCAL VOC 2007和2012数据集上测试我们的方法。我们证明了该方法可以在不损害性能的情况下展现出有希望的潜在结构。

##### URL
[http://arxiv.org/abs/1711.05226](http://arxiv.org/abs/1711.05226)

##### PDF
[http://arxiv.org/pdf/1711.05226](http://arxiv.org/pdf/1711.05226)

