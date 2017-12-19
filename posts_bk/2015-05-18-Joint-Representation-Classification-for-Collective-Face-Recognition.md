---
layout: post
title: "Joint Representation Classification for Collective Face Recognition"
date: 2015-05-18 13:04:04
categories: arXiv_CV
tags: arXiv_CV Sparse Face Optimization Classification Relation Recognition Face_Recognition
author: Liping Wang, Songcan Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse representation based classification (SRC) is popularly used in many applications such as face recognition, and implemented in two steps: representation coding and classification. For a given set of testing images, SRC codes every image over the base images as a sparse representation then classifies it to the class with the least representation error. This scheme utilizes an individual representation rather than the collective one to classify such a set of images, doing so obviously ignores the correlation among the given images. In this paper, a joint representation classification (JRC) for collective face recognition is proposed. JRC takes the correlation of multiple images as well as a single representation into account. Under the assumption that the given face images are generally related to each other, JRC codes all the testing images over the base images simultaneously to facilitate recognition. To this end, the testing inputs are aligned into a matrix and the joint representation coding is formulated to a generalized $l_{2,q}-l_{2,p}$-minimization problem. To uniformly solve the induced optimization problems for any $q\in[1,2]$ and $p\in (0,2]$, an iterative quadratic method (IQM) is developed. IQM is proved to be a strict descent algorithm with convergence to the optimal solution. Moreover, a more practical IQM is proposed for large-scale case. Experimental results on three public databases show that the JRC with practical IQM no only saves much computational cost but also achieves better performance in collective face recognition than the state-of-the-arts.

##### Abstract (translated by Google)
基于稀疏表示的分类（SRC）被广泛应用于许多应用中，如人脸识别，分两步实现：表示编码和分类。对于给定的一组测试图像，SRC将基本图像上的每个图像编码为稀疏表示，然后将其分类为具有最小表示错误的类。该方案利用个体表示而不是集体图像对这样的图像集合进行分类，这样做显然忽略了给定图像之间的相关性。本文提出了一种用于集体人脸识别的联合表示分类（JRC）。 JRC将多个图像的相关性以及单个表示考虑在内。在给定人脸图像通常相互关联的假设下，JRC将所有测试图像同时编码在基本图像上以便于识别。为此，将测试输入对齐到矩阵中，并且联合表示编码被制定为广义的{1，2，q} -l_ {2，p} $最小化问题。为了在[1,2] $ $和$ p \（0,2] $中均匀求解任意$ q \的诱导优化问题，我们开发了一个迭代二次方法（IQM），IQM被证明是一个严格的下降算法收敛到最优解，并且提出了一种更为实用的IQM算法，在三个公共数据库上的实验结果表明，具有实际IQM的JRC不仅节省了大量的计算成本，而且在集体人脸识别方面也取得了较好的性能最先进的技术。

##### URL
[https://arxiv.org/abs/1505.04617](https://arxiv.org/abs/1505.04617)

##### PDF
[https://arxiv.org/pdf/1505.04617](https://arxiv.org/pdf/1505.04617)

