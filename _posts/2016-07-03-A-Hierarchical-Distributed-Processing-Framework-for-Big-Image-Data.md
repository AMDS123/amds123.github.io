---
layout: post
title: "A Hierarchical Distributed Processing Framework for Big Image Data"
date: 2016-07-03 02:16:49
categories: arXiv_CV
tags: arXiv_CV
author: Le Dong, Zhiyu Lin, Yan Liang, Ling He, Ning Zhang, Qi Chen, Xiaochun Cao, Ebroul lzquierdo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces an effective processing framework nominated ICP (Image Cloud Processing) to powerfully cope with the data explosion in image processing field. While most previous researches focus on optimizing the image processing algorithms to gain higher efficiency, our work dedicates to providing a general framework for those image processing algorithms, which can be implemented in parallel so as to achieve a boost in time efficiency without compromising the results performance along with the increasing image scale. The proposed ICP framework consists of two mechanisms, i.e. SICP (Static ICP) and DICP (Dynamic ICP). Specifically, SICP is aimed at processing the big image data pre-stored in the distributed system, while DICP is proposed for dynamic input. To accomplish SICP, two novel data representations named P-Image and Big-Image are designed to cooperate with MapReduce to achieve more optimized configuration and higher efficiency. DICP is implemented through a parallel processing procedure working with the traditional processing mechanism of the distributed system. Representative results of comprehensive experiments on the challenging ImageNet dataset are selected to validate the capacity of our proposed ICP framework over the traditional state-of-the-art methods, both in time efficiency and quality of results.

##### Abstract (translated by Google)
本文介绍了一个有效的处理框架提名ICP（图像云处理），以有力地应对图像处理领域的数据爆炸。虽然大多数以前的研究集中在优化图像处理算法以获得更高的效率，但是我们的工作致力于为这些图像处理算法提供通用框架，这些算法可以并行实现，从而在不影响结果性能的情况下提高时间效率随着形象规模的不断扩大。拟议的ICP框架由两个机制组成，即SICP（静态ICP）和DICP（动态ICP）。具体来说，SICP旨在处理预先存储在分布式系统中的大图像数据，而DICP则被提出用于动态输入。为了实现SICP，设计了两个新的数据表示P-Image和Big-Image，与MapReduce配合使用，实现更优化的配置和更高的效率。 DICP是通过与分布式系统的传统处理机制一起工作的并行处理程序来实现的。选择具有挑战性的ImageNet数据集的全面实验的代表性结果，以验证我们提议的ICP框架相对于传统的最先进的方法的能力，无论是在时间效率和结果质量。

##### URL
[https://arxiv.org/abs/1607.00577](https://arxiv.org/abs/1607.00577)

##### PDF
[https://arxiv.org/pdf/1607.00577](https://arxiv.org/pdf/1607.00577)

