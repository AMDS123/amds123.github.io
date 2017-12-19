---
layout: post
title: "Structured Attentions for Visual Question Answering"
date: 2017-08-07 11:14:11
categories: arXiv_CV
tags: arXiv_CV QA Attention Inference Relation VQA
author: Chen Zhu, Yanpeng Zhao, Shuaiyi Huang, Kewei Tu, Yi Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Visual attention, which assigns weights to image regions according to their relevance to a question, is considered as an indispensable part by most Visual Question Answering models. Although the questions may involve complex relations among multiple regions, few attention models can effectively encode such cross-region relations. In this paper, we demonstrate the importance of encoding such relations by showing the limited effective receptive field of ResNet on two datasets, and propose to model the visual attention as a multivariate distribution over a grid-structured Conditional Random Field on image regions. We demonstrate how to convert the iterative inference algorithms, Mean Field and Loopy Belief Propagation, as recurrent layers of an end-to-end neural network. We empirically evaluated our model on 3 datasets, in which it surpasses the best baseline model of the newly released CLEVR dataset by 9.5%, and the best published model on the VQA dataset by 1.25%. Source code is available at https: //github.com/zhuchen03/vqa-sva.

##### Abstract (translated by Google)
视觉注意力，根据它们与问题的相关性给图像区域分配权重，被视为大多数视觉问题回答模型不可或缺的部分。虽然这些问题可能涉及到多个地区之间的复杂关系，但很少有关注模型可以有效地编码这种跨地域关系。在本文中，我们通过在两个数据集上展示ResNet有限的有效接收场来证明编码这种关系的重要性，并且提出将视觉注意力模拟为图像区域上的网格结构条件随机场上的多变量分布。我们演示了如何将迭代推理算法，平均场和Loopy信念传播转换为端到端神经网络的递归层。我们根据3个数据集对模型进行了实证评估，其中新发布的CLEVR数据集的最佳基线模型超过了9.5％，VQA数据集上的最佳发布模型数量为1.25％。源代码可在https：//github.com/zhuchen03/vqa-sva获得。

##### URL
[https://arxiv.org/abs/1708.02071](https://arxiv.org/abs/1708.02071)

##### PDF
[https://arxiv.org/pdf/1708.02071](https://arxiv.org/pdf/1708.02071)

