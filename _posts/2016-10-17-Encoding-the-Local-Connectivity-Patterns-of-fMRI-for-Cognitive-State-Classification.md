---
layout: post
title: "Encoding the Local Connectivity Patterns of fMRI for Cognitive State Classification"
date: 2016-10-17 10:08:09
categories: arXiv_CV
tags: arXiv_CV Classification Relation
author: Itir Onal Ertugrul, Mete Ozay, Fatos T. Yarman Vural
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a novel framework to encode the local connectivity patterns of brain, using Fisher Vectors (FV), Vector of Locally Aggregated Descriptors (VLAD) and Bag-of-Words (BoW) methods. We first obtain local descriptors, called Mesh Arc Descriptors (MADs) from fMRI data, by forming local meshes around anatomical regions, and estimating their relationship within a neighborhood. Then, we extract a dictionary of relationships, called \textit{brain connectivity dictionary} by fitting a generative Gaussian mixture model (GMM) to a set of MADs, and selecting the codewords at the mean of each component of the mixture. Codewords represent the connectivity patterns among anatomical regions. We also encode MADs by VLAD and BoW methods using the k-Means clustering. We classify the cognitive states of Human Connectome Project (HCP) task fMRI dataset, where we train support vector machines (SVM) by the encoded MADs. Results demonstrate that, FV encoding of MADs can be successfully employed for classification of cognitive tasks, and outperform the VLAD and BoW representations. Moreover, we identify the significant Gaussians in mixture models by computing energy of their corresponding FV parts, and analyze their effect on classification accuracy. Finally, we suggest a new method to visualize the codewords of brain connectivity dictionary.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个新的框架来编码局部连接模式的大脑，使用费舍尔载体（FV），矢量局部聚合描述符（VLAD）和袋字（BoW）的方法。我们首先从fMRI数据中获得称为网格弧描述符（MAD）的局部描述符，通过在解剖区域周围形成局部网格并估计它们在邻域内的关系。然后，我们通过将生成的高斯混合模型（GMM）拟合到一组MAD，并且在混合的每个分量的平均值处选择码字，来提取关系字典，称为\ textit {脑连接字典}。码字表示解剖区域之间的连接模式。我们还使用k-Means聚类，通过VLAD和BoW方法对MAD进行编码。我们对人类连接项目（HCP）任务fMRI数据集的认知状态进行分类，在这里我们通过编码的MAD训练支持向量机（SVM）。结果表明，MAD的FV编码可以成功地用于认知任务的分类，并且胜过VLAD和BoW表示。此外，我们通过计算相应的FV部分的能量来识别混合模型中的显着高斯，并分析它们对分类精度的影响。最后，我们提出一种新的方法来显示大脑连接字典的代码字。

##### URL
[https://arxiv.org/abs/1610.05036](https://arxiv.org/abs/1610.05036)

##### PDF
[https://arxiv.org/pdf/1610.05036](https://arxiv.org/pdf/1610.05036)

