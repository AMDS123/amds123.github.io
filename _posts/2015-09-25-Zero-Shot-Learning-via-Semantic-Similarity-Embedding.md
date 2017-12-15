---
layout: post
title: "Zero-Shot Learning via Semantic Similarity Embedding"
date: 2015-09-25 20:26:08
categories: arXiv_CV
tags: arXiv_CV Embedding Recognition
author: Ziming Zhang, Venkatesh Saligrama
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we consider a version of the zero-shot learning problem where seen class source and target domain data are provided. The goal during test-time is to accurately predict the class label of an unseen target domain instance based on revealed source domain side information (\eg attributes) for unseen classes. Our method is based on viewing each source or target data as a mixture of seen class proportions and we postulate that the mixture patterns have to be similar if the two instances belong to the same unseen class. This perspective leads us to learning source/target embedding functions that map an arbitrary source/target domain data into a same semantic space where similarity can be readily measured. We develop a max-margin framework to learn these similarity functions and jointly optimize parameters by means of cross validation. Our test results are compelling, leading to significant improvement in terms of accuracy on most benchmark datasets for zero-shot recognition.

##### Abstract (translated by Google)
在本文中，我们考虑一个零点学习问题的版本，其中提供了可见的类源数据和目标数据域。测试期间的目标是基于揭示的源域边信息（\例如属性）来准确地预测未看到的目标域实例的类别标签。我们的方法是基于将每个源或目标数据视为所看到的类比例的混合，并且假定如果两个实例属于相同的看不见的类，混合模式必须是相似的。这种观点导致我们学习源/目标嵌入函数，将任意源/目标域数据映射到相似性可以很容易测量的相同语义空间。我们开发了一个最大边缘框架来学习这些相似函数，并通过交叉验证来联合优化参数。我们的测试结果令人信服，在大多数零点识别基准数据集的精度方面都有显着提高。

##### URL
[https://arxiv.org/abs/1509.04767](https://arxiv.org/abs/1509.04767)

##### PDF
[https://arxiv.org/pdf/1509.04767](https://arxiv.org/pdf/1509.04767)

