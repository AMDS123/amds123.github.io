---
layout: post
title: "Computational Cost Reduction in Learned Transform Classifications"
date: 2016-04-30 15:03:29
categories: arXiv_CV
tags: arXiv_CV Optimization Classification
author: Emerson Lopes Machado, Cristiano Jacques Miosso, Ricardo von Borries, Murilo Coutinho, Pedro de Azevedo Berger, Thiago Marques, Ricardo Pezzuol Jacobi
mathjax: true
---

* content
{:toc}

##### Abstract
We present a theoretical analysis and empirical evaluations of a novel set of techniques for computational cost reduction of classifiers that are based on learned transform and soft-threshold. By modifying optimization procedures for dictionary and classifier training, as well as the resulting dictionary entries, our techniques allow to reduce the bit precision and to replace each floating-point multiplication by a single integer bit shift. We also show how the optimization algorithms in some dictionary training methods can be modified to penalize higher-energy dictionaries. We applied our techniques with the classifier Learning Algorithm for Soft-Thresholding, testing on the datasets used in its original paper. Our results indicate it is feasible to use solely sums and bit shifts of integers to classify at test time with a limited reduction of the classification accuracy. These low power operations are a valuable trade off in FPGA implementations as they increase the classification throughput while decrease both energy consumption and manufacturing cost.

##### Abstract (translated by Google)
我们提出了一套基于学习变换和软阈值的分类器计算成本降低的一套新技术的理论分析和经验评估。通过修改字典和分类器训练的优化程序以及生成的字典条目，我们的技术允许降低比特精度，并用一个整数位移代替每个浮点乘法。我们还展示了如何修改一些字典训练方法中的优化算法来惩罚更高能量的字典。我们应用我们的技术与分类器学习算法软阈值，测试在其原始文件中使用的数据集。我们的结果表明，使用整数和位整数的移位在测试时间进行分类是可行的，分类精度有限的降低。这些低功耗操作在FPGA实现中是一个有价值的交易，因为它们增加了分类吞吐量，同时降低了能耗和制造成本。

##### URL
[https://arxiv.org/abs/1504.06779](https://arxiv.org/abs/1504.06779)

##### PDF
[https://arxiv.org/pdf/1504.06779](https://arxiv.org/pdf/1504.06779)

