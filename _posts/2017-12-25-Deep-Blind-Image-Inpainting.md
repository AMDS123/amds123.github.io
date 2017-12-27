---
layout: post
title: "Deep Blind Image Inpainting"
date: 2017-12-25 14:45:37
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Yang Liu, Jinshan Pan, Zhixun Su
mathjax: true
---

* content
{:toc}

##### Abstract
Image inpainting is a challenging problem as it needs to fill the information of the corrupted regions. Most of the existing inpainting algorithms assume that the positions of the corrupted regions are known. Different from the existing methods that usually make some assumptions on the corrupted regions, we present an efficient blind image inpainting algorithm to directly restore a clear image from a corrupted input. Our algorithm is motivated by the residual learning algorithm which aims to learn the missing infor- mation in corrupted regions. However, directly using exist- ing residual learning algorithms in image restoration does not well solve this problem as little information is available in the corrupted regions. To solve this problem, we introduce an encoder and decoder architecture to capture more useful information and develop a robust loss function to deal with outliers. Our algorithm can predict the missing information in the corrupted regions, thus facilitating the clear image restoration. Both qualitative and quantitative experimental demonstrate that our algorithm can deal with the corrupted regions of arbitrary shapes and performs favorably against state-of-the-art methods.

##### Abstract (translated by Google)
图像修复是一个具有挑战性的问题，因为它需要填写已损坏区域的信息。大多数现有的修复算法都假定已知的已损坏区域的位置。与现有方法通常对损坏的区域进行一些假设不同，我们提出了一种有效的盲图像修复算法，以直接从损坏的输入中恢复清晰的图像。我们的算法的动机是残留学习算法，旨在了解损坏地区的遗漏信息。然而，在图像恢复中直接使用现有的残差学习算法并不能很好地解决这个问题，因为在损坏的区域中可用的信息很少。为了解决这个问题，我们引入了一个编码器和解码器架构来捕获更多有用的信息，并开发一个强大的丢失函数来处理异常值。我们的算法可以预测损坏区域中的丢失信息，从而促进清晰的图像恢复。定性和定量实验证明，我们的算法可以处理任意形状的损坏区域，并且有利于抵抗最先进的方法。

##### URL
[http://arxiv.org/abs/1712.09078](http://arxiv.org/abs/1712.09078)

##### PDF
[http://arxiv.org/pdf/1712.09078](http://arxiv.org/pdf/1712.09078)

