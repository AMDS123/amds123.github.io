---
layout: post
title: "Interpretable R-CNN"
date: 2017-11-14 17:59:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Tianfu Wu, Xilai Li, Xi Song, Wei Sun, Liang Dong, Bo Li
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method of learning qualitatively interpretable models in object detection using popular two-stage region-based ConvNet detection systems (i.e., R-CNN). R-CNN consists of a region proposal network and a RoI (Region-of-Interest) prediction network.By interpretable models, we focus on weakly-supervised extractive rationale generation, that is learning to unfold latent discriminative part configurations of object instances automatically and simultaneously in detection without using any supervision for part configurations. We utilize a top-down hierarchical and compositional grammar model embedded in a directed acyclic AND-OR Graph (AOG) to explore and unfold the space of latent part configurations of RoIs. We propose an AOGParsing operator to substitute the RoIPooling operator widely used in R-CNN, so the proposed method is applicable to many state-of-the-art ConvNet based detection systems. The AOGParsing operator aims to harness both the explainable rigor of top-down hierarchical and compositional grammar models and the discriminative power of bottom-up deep neural networks through end-to-end training. In detection, a bounding box is interpreted by the best parse tree derived from the AOG on-the-fly, which is treated as the extractive rationale generated for interpreting detection. In learning, we propose a folding-unfolding method to train the AOG and ConvNet end-to-end. In experiments, we build on top of the R-FCN and test the proposed method on the PASCAL VOC 2007 and 2012 datasets with performance comparable to state-of-the-art methods.

##### Abstract (translated by Google)
本文提出了一种使用流行的两阶段基于区域的ConvNet检测系统（即R-CNN）在对象检测中学习定性可解释模型的方法。 R-CNN由一个区域提议网络和一个RoI（Region-of-Interest）预测网络组成。通过可解释模型，我们关注弱监督提取的基本生成过程，即学习自动展开对象实例的潜在判别部分配置。同时进行检测，无需对部件配置进行任何监控。我们利用一个嵌入在有向无环AND-OR图（AOG）中的自顶向下的层次和组合语法模型来探索和展示ROI的潜在部分配置的空间。我们提出了一个AOGParsing算子来代替R-CNN中广泛使用的RoIPooling算子，所以该方法适用于许多最先进的基于ConvNet的检测系统。 AOGParsing算子旨在利用自上而下的层次和组合语法模型的可解释的严格性和通过端到端训练的自下而上的深度神经网络的区分能力。在检测过程中，边界框由AOG即时导出的最佳解析树来解释，这被视为解释检测所产生的抽取原理。在学习中，我们提出了一种折叠展开的方法来训练AOG和ConvNet的端到端。在实验中，我们建立在R-FCN之上，并在PASCAL VOC 2007和2012数据集上测试所提出的方法，其性能与最先进的方法相当。

##### URL
[https://arxiv.org/abs/1711.05226](https://arxiv.org/abs/1711.05226)

##### PDF
[https://arxiv.org/pdf/1711.05226](https://arxiv.org/pdf/1711.05226)

