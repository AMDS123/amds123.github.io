---
layout: post
title: "Privacy-Preserving Visual Learning Using Doubly Permuted Homomorphic Encryption"
date: 2017-07-28 15:39:23
categories: arXiv_CV
tags: arXiv_CV Sparse Recognition
author: Ryo Yonetani, Vishnu Naresh Boddeti, Kris M. Kitani, Yoichi Sato
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a privacy-preserving framework for learning visual classifiers by leveraging distributed private image data. This framework is designed to aggregate multiple classifiers updated locally using private data and to ensure that no private information about the data is exposed during and after its learning procedure. We utilize a homomorphic cryptosystem that can aggregate the local classifiers while they are encrypted and thus kept secret. To overcome the high computational cost of homomorphic encryption of high-dimensional classifiers, we (1) impose sparsity constraints on local classifier updates and (2) propose a novel efficient encryption scheme named doubly-permuted homomorphic encryption (DPHE) which is tailored to sparse high-dimensional data. DPHE (i) decomposes sparse data into its constituent non-zero values and their corresponding support indices, (ii) applies homomorphic encryption only to the non-zero values, and (iii) employs double permutations on the support indices to make them secret. Our experimental evaluation on several public datasets shows that the proposed approach achieves comparable performance against state-of-the-art visual recognition methods while preserving privacy and significantly outperforms other privacy-preserving methods.

##### Abstract (translated by Google)
我们提出了一个隐私保护框架，通过利用分布式私人图像数据来学习视觉分类器。这个框架被设计用于聚合​​本地使用私人数据更新的多个分类器，并且确保在其学习过程期间和之后不暴露关于数据的私人信息。我们使用一个同态的密码系统，它可以聚合本地分类器，同时它们被加密并保密。为克服高维分类器同态加密的高计算代价，我们（1）对局部分类器更新施加稀疏约束，（2）提出了一种新的高效的加密方案，称为双重置换同态加密（DPHE）高维数据。 DPHE（i）将稀疏数据分解为其构成的非零值及其相应的支持指数，（ii）将同态加密仅应用于非零值，以及（iii）在支持指数上使用双重排列使其成为秘密。我们对多个公共数据集的实验评估表明，所提出的方法在保持隐私的同时，与最先进的视觉识别方法相比，具有可比较的性能，并且明显优于其他隐私保护方法。

##### URL
[https://arxiv.org/abs/1704.02203](https://arxiv.org/abs/1704.02203)

##### PDF
[https://arxiv.org/pdf/1704.02203](https://arxiv.org/pdf/1704.02203)

