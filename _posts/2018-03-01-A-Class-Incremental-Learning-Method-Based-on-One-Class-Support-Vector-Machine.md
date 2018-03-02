---
layout: post
title: "A Class-Incremental Learning Method Based on One Class Support Vector Machine"
date: 2018-03-01 01:50:42
categories: arXiv_CV
tags: arXiv_CV
author: Chengfei Yao, Jie Zou, Yanan Luo, Tao Li, Gang Bai
mathjax: true
---

* content
{:toc}

##### Abstract
A method based on one class support vector machine (OCSVM) is proposed for class incremental learning. Several OCSVM models divide the input space into several parts. Then, the 1VS1 classifiers are constructed for the confuse part by using the support vectors. During the class incremental learning process, the OCSVM of the new class is trained at first. Then the support vectors of the old classes and the support vectors of the new class are reused to train 1VS1 classifiers for the confuse part. In order to bring more information to the certain support vectors, the support vectors are at the boundary of the distribution of samples as much as possible when the OCSVM is built. Compared with the traditional methods, the proposed method retains the original model and thus reduces memory consumption and training time cost. Various experiments on different datasets also verify the efficiency of the proposed method.

##### Abstract (translated by Google)
提出了一种基于一类支持向量机（OCSVM）的类增量学习方法。几个OCSVM模型将输入空间分成几个部分。然后，通过使用支持向量为混淆部分构建1VS1分类器。在课堂增量学习过程中，新课堂的OCSVM首先被训练。然后重新使用旧类的支持向量和新类的支持向量来训练混淆部分的1VS1分类器。为了给特定的支持向量带来更多的信息，在构建OCSVM时，支持向量尽可能地处于样本分布的边界处。与传统方法相比，该方法保留了原始模型，从而减少了内存消耗和训练时间成本。不同数据集上的各种实验也验证了所提出的方法的效率。

##### URL
[http://arxiv.org/abs/1803.00159](http://arxiv.org/abs/1803.00159)

##### PDF
[http://arxiv.org/pdf/1803.00159](http://arxiv.org/pdf/1803.00159)

