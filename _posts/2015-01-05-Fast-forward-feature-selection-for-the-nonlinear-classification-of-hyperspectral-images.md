---
layout: post
title: "Fast forward feature selection for the nonlinear classification of hyperspectral images"
date: 2015-01-05 13:37:37
categories: arXiv_CV
tags: arXiv_CV Classification
author: Mathieu Fauvel, Clement Dechesne, Anthony Zullo, Frédéric Ferraty
mathjax: true
---

* content
{:toc}

##### Abstract
A fast forward feature selection algorithm is presented in this paper. It is based on a Gaussian mixture model (GMM) classifier. GMM are used for classifying hyperspectral images. The algorithm selects iteratively spectral features that maximizes an estimation of the classification rate. The estimation is done using the k-fold cross validation. In order to perform fast in terms of computing time, an efficient implementation is proposed. First, the GMM can be updated when the estimation of the classification rate is computed, rather than re-estimate the full model. Secondly, using marginalization of the GMM, sub models can be directly obtained from the full model learned with all the spectral features. Experimental results for two real hyperspectral data sets show that the method performs very well in terms of classification accuracy and processing time. Furthermore, the extracted model contains very few spectral channels.

##### Abstract (translated by Google)
本文提出了一种快速前向特征选择算法。它基于高斯混合模型（GMM）分类器。 GMM用于对高光谱图像进行分类。算法选择最大化分类率估计的迭代谱特征。估计是使用k倍交叉验证完成的。为了在计算时间方面快速执行，提出了一种有效的实现。首先，在计算分类率的估计值时可以更新GMM，而不是重新估计整个模型。其次，利用GMM的边缘化，可以从全谱模型中直接获得子模型。两个真实高光谱数据集的实验结果表明，该方法在分类精度和处理时间方面表现非常好。此外，提取的模型包含非常少的频谱信道。

##### URL
[https://arxiv.org/abs/1501.00857](https://arxiv.org/abs/1501.00857)

##### PDF
[https://arxiv.org/pdf/1501.00857](https://arxiv.org/pdf/1501.00857)

