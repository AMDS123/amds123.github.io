---
layout: post
title: "Autoencoders for music sound synthesis: a comparison of linear, shallow, deep and variational models"
date: 2018-06-11 16:39:16
categories: arXiv_SD
tags: arXiv_SD Regularization Knowledge Optimization
author: Fanny Roche (1 and 2), Thomas Hueber (1), Samuel Limier (2), Laurent Girin (1 and 3) ((1) Univ. Grenoble Alpes, CNRS, Grenoble INP, GIPSA-lab, Grenoble, France, (2) Arturia, Meylan, France, (3) INRIA, Perception Team, Montbonnot, France)
mathjax: true
---

* content
{:toc}

##### Abstract
This study investigates the use of non-linear unsupervised dimensionality reduction techniques to compress a music dataset into a low-dimensional representation, and its use for the synthesis of new sounds. We systematically compare (shallow) autoencoders (AE) and deep autoencoders (DAE) with principal component analysis (PCA) for representing the high-resolution short-term amplitude spectrum of a large and dense dataset of music notes into a lower-dimensional vector (and then convert it back to a synthetic amplitude spectrum used for sound resynthesis). In addition, we report results obtained with variational autoencoders (VAE) which to our knowledge have never been considered for processing musical sounds. Our experiments were conducted on the publicly available multi-instrument and multi-pitch database NSynth. Interestingly and contrary to the recent literature on image processing, they showed that PCA systematically outperforms shallow AE and that only a deep architecture (DAE) can lead to a lower reconstruction error. The optimization criterion in deep VAE being the sum of the reconstruction error and a regularization term, it naturally leads to a lower reconstruction accuracy than DAE but we show that VAEs are still able to outperform PCA while providing a low-dimensional latent space with nice "usability" properties.

##### Abstract (translated by Google)
本研究调查了使用非线性无监督降维技术将音乐数据集压缩为低维表示，并将其用于合成新声音。我们将（浅）自编码器（AE）和深自编码器（DAE）与主成分分析（PCA）进行了比较，以将音乐笔记大而密集的数据集的高分辨率短时振幅谱表示为较低维向量然后将其转换回用于声音再合成的合成幅度谱）。另外，我们报告了使用变化自编码器（VAE）获得的结果，据我们所知，这些结果从未被用于处理音乐声音。我们的实验是在公开可用的多仪器和多节距数据库NSynth上进行的。有趣的是，与最近有关图像处理的文献相反，他们表明PCA系统地优于浅层AE，并且只有深层结构（DAE）才能导致较低的重建误差。在深VAE中的优化标准是重构误差和正则化项的总和，这自然导致比DAE更低的重建准确度，但是我们表明VAE仍然能够胜过PCA，同时提供低维潜在空间，具有良好的“可用性“属性。

##### URL
[http://arxiv.org/abs/1806.04096](http://arxiv.org/abs/1806.04096)

##### PDF
[http://arxiv.org/pdf/1806.04096](http://arxiv.org/pdf/1806.04096)

