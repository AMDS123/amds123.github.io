---
layout: post
title: "Self-Taught Support Vector Machine"
date: 2017-10-12 11:12:30
categories: arXiv_CV
tags: arXiv_CV Classification
author: Parvin Razzaghi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a new approach for classification of target task using limited labeled target data as well as enormous unlabeled source data is proposed which is called self-taught learning. The target and source data can be drawn from different distributions. In the previous approaches, covariate shift assumption is considered where the marginal distributions p(x) change over domains and the conditional distributions p(y|x) remain the same. In our approach, we propose a new objective function which simultaneously learns a common space T(.) where the conditional distributions over domains p(T(x)|y) remain the same and learns robust SVM classifiers for target task using both source and target data in the new representation. Hence, in the proposed objective function, the hidden label of the source data is also incorporated. We applied the proposed approach on Caltech-256, MSRC+LMO datasets and compared the performance of our algorithm to the available competing methods. Our method has a superior performance to the successful existing algorithms.

##### Abstract (translated by Google)
本文提出了一种新的基于有限标注目标数据的目标任务分类方法和巨大的无标签源数据分类方法，称为自学习。目标和源数据可以从不同的分布中得出。在先前的方法中，协变量假设被认为是边界分布p（x）在域上变化，并且条件分布p（y | x）保持相同。在我们的方法中，我们提出了一个新的目标函数，它同时学习一个公共空间T（。），其中域p（T（x）| y）上的条件分布保持不变，并且学习目标任务的鲁棒SVM分类器，目标数据在新的表示。因此，在所提出的目标函数中，源数据的隐藏标签也被并入。我们将所提出的方法应用于Caltech-256，MSRC + LMO数据集，并将我们的算法的性能与可用的竞争方法进行比较。我们的方法比现有的成功算法具有更好的性能。

##### URL
[https://arxiv.org/abs/1710.04450](https://arxiv.org/abs/1710.04450)

##### PDF
[https://arxiv.org/pdf/1710.04450](https://arxiv.org/pdf/1710.04450)

