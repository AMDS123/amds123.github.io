---
layout: post
title: "Learning Better Encoding for Approximate Nearest Neighbor Search with Dictionary Annealing"
date: 2015-07-06 13:25:35
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Shicong Liu, Hongtao Lu
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel dictionary optimization method for high-dimensional vector quantization employed in approximate nearest neighbor (ANN) search. Vector quantization methods first seek a series of dictionaries, then approximate each vector by a sum of elements selected from these dictionaries. An optimal series of dictionaries should be mutually independent, and each dictionary should generate a balanced encoding for the target dataset. Existing methods did not explicitly consider this. To achieve these goals along with minimizing the quantization error (residue), we propose a novel dictionary optimization method called \emph{Dictionary Annealing} that alternatively "heats up" a single dictionary by generating an intermediate dataset with residual vectors, "cools down" the dictionary by fitting the intermediate dataset, then extracts the new residual vectors for the next iteration. Better codes can be learned by DA for the ANN search tasks. DA is easily implemented on GPU to utilize the latest computing technology, and can easily extended to an online dictionary learning scheme. We show by experiments that our optimized dictionaries substantially reduce the overall quantization error. Jointly used with residual vector quantization, our optimized dictionaries lead to a better approximate nearest neighbor search performance compared to the state-of-the-art methods.

##### Abstract (translated by Google)
我们介绍了一种新颖的用于近似最近邻（ANN）搜索的高维矢量量化的字典优化方法。矢量量化方法首先寻找一系列字典，然后通过从这些字典中选择的元素的总和来近似每个矢量。最佳系列词典应该是相互独立的，每个词典应该为目标数据集生成一个平衡的编码。现有方法没有明确考虑这一点。为了实现这些目标，同时尽量减少量化误差（残差），我们提出了一种名为\ emph {Dictionary Annealing}的新型字典优化方法，通过生成具有残差向量的中间数据集“冷却”单个字典，通过拟合中间数据集，然后提取新的残差向量进行下一次迭代。 DA搜索任务可以通过DA学习更好的代码。 DA易于在GPU上实现，利用最新的计算技术，可以轻松扩展到在线字典学习方案。我们通过实验显示，我们优化的词典大大减少了整体量化误差。联合使用残差矢量量化，与最先进的方法相比，我们优化的字典导致更好的近似最近邻搜索性能。

##### URL
[https://arxiv.org/abs/1507.01442](https://arxiv.org/abs/1507.01442)

##### PDF
[https://arxiv.org/pdf/1507.01442](https://arxiv.org/pdf/1507.01442)

