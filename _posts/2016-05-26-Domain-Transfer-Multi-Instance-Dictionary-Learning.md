---
layout: post
title: "Domain Transfer Multi-Instance Dictionary Learning"
date: 2016-05-26 18:28:49
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification
author: Ke Wang, Jiayong Liu, Daniel González
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we invest the domain transfer learning problem with multi-instance data. We assume we already have a well-trained multi-instance dictionary and its corresponding classifier from the source domain, which can be used to represent and classify the bags. But it cannot be directly used to the target domain. Thus we propose to adapt them to the target domain by adding an adaptive term to the source domain classifier. The adaptive function is a linear function based a domain transfer multi-instance dictionary. Given a target domain bag, we first map it to a bag-level feature space using the domain transfer dictionary, and then apply a the linear adaptive function to its bag-level feature vector. To learn the domain-transfer dictionary and the adaptive function parameter, we simultaneously minimize the average classification error of the target domain classifier over the target domain training set, and the complexities of both the adaptive function parameter and the domain transfer dictionary. The minimization problem is solved by an iterative algorithm which update the dictionary and the function parameter alternately. Experiments over several benchmark data sets show the advantage of the proposed method over existing state-of-the-art domain transfer multi-instance learning methods.

##### Abstract (translated by Google)
在这篇论文中，我们将域转移学习问题用于多实例数据。我们假设我们已经有一个训练有素的多实例字典及其来源域的相应分类器，可以用来表示和分类行李。但它不能直接用于目标域。因此，我们建议通过为源域分类器添加一个自适应项来使它们适应目标域。自适应函数是基于域转移多实例字典的线性函数。给定一个目标域包，我们首先使用域转移字典将其映射到一个包级特征空间，然后将线性自适应函数应用到它的包级特征向量。为了学习域转移字典和自适应函数参数，我们同时最小化目标域分类器在目标域训练集上的平均分类误差以及自适应函数参数和域转移字典的复杂性。最小化问题通过交替地更新字典和函数参数的迭代算法来解决。在几个基准数据集上的实验显示了所提出的方法相对于现有的最先进的域转移多实例学习方法的优点。

##### URL
[https://arxiv.org/abs/1605.08397](https://arxiv.org/abs/1605.08397)

##### PDF
[https://arxiv.org/pdf/1605.08397](https://arxiv.org/pdf/1605.08397)

