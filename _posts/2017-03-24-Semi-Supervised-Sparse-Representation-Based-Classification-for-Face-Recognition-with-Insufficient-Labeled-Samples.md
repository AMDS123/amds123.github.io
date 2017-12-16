---
layout: post
title: "Semi-Supervised Sparse Representation Based Classification for Face Recognition with Insufficient Labeled Samples"
date: 2017-03-24 06:26:12
categories: arXiv_CV
tags: arXiv_CV Sparse Face Classification Recognition Face_Recognition
author: Yuan Gao, Jiayi Ma, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of face recognition when there is only few, or even only a single, labeled examples of the face that we wish to recognize. Moreover, these examples are typically corrupted by nuisance variables, both linear (i.e., additive nuisance variables such as bad lighting, wearing of glasses) and non-linear (i.e., non-additive pixel-wise nuisance variables such as expression changes). The small number of labeled examples means that it is hard to remove these nuisance variables between the training and testing faces to obtain good recognition performance. To address the problem we propose a method called Semi-Supervised Sparse Representation based Classification (S$^3$RC). This is based on recent work on sparsity where faces are represented in terms of two dictionaries: a gallery dictionary consisting of one or more examples of each person, and a variation dictionary representing linear nuisance variables (e.g., different lighting conditions, different glasses). The main idea is that (i) we use the variation dictionary to characterize the linear nuisance variables via the sparsity framework, then (ii) prototype face images are estimated as a gallery dictionary via a Gaussian Mixture Model (GMM), with mixed labeled and unlabeled samples in a semi-supervised manner, to deal with the non-linear nuisance variations between labeled and unlabeled samples. We have done experiments with insufficient labeled samples, even when there is only a single labeled sample per person. Our results on the AR, Multi-PIE, CAS-PEAL, and LFW databases demonstrate that the proposed method is able to deliver significantly improved performance over existing methods.

##### Abstract (translated by Google)
这篇论文解决了人脸识别的问题，当我们想要识别的人脸只有少数，甚至只有一个，标记的例子。而且，这些例子通常受到干扰变量的干扰，既是线性的（即，加性干扰变量，例如不良照明，佩戴眼镜），也是非线性（即非加性像素方式的干扰变量，如表情变化）。少数标记的例子意味着在训练和测试面之间很难去除这些令人讨厌的变量以获得良好的识别性能。为了解决这个问题，我们提出了一种叫做半监督稀疏表示的分类方法（S $ ^ 3 $ RC）。这是基于最近关于稀疏性的工作，其中以两个词典表示脸部：由每个人的一个或多个示例组成的画廊词典，以及表示线性讨厌变量（例如不同光照条件，不同眼镜）的变体词典。主要思想是：（1）利用变异字典通过稀疏框架表征线性滋扰变量，然后（2）通过高斯混合模型（GMM）将原型人脸图像估计为图库字典，未标记的样本以半监督的方式来处理标记和未标记样本之间的非线性滋扰差异。我们做了标签样本不足的实验，即使每个人只有一个标签样本。我们在AR，Multi-PIE，CAS-PEAL和LFW数据库上的结果表明，与现有方法相比，所提出的方法能够显着提高性能。

##### URL
[https://arxiv.org/abs/1609.03279](https://arxiv.org/abs/1609.03279)

##### PDF
[https://arxiv.org/pdf/1609.03279](https://arxiv.org/pdf/1609.03279)

