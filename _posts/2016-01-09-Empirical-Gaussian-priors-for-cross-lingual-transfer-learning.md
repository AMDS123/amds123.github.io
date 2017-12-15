---
layout: post
title: "Empirical Gaussian priors for cross-lingual transfer learning"
date: 2016-01-09 23:34:05
categories: arXiv_SD
tags: arXiv_SD Regularization Transfer_Learning Language_Model
author: Anders Søgaard
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence model learning algorithms typically maximize log-likelihood minus the norm of the model (or minimize Hamming loss + norm). In cross-lingual part-of-speech (POS) tagging, our target language training data consists of sequences of sentences with word-by-word labels projected from translations in $k$ languages for which we have labeled data, via word alignments. Our training data is therefore very noisy, and if Rademacher complexity is high, learning algorithms are prone to overfit. Norm-based regularization assumes a constant width and zero mean prior. We instead propose to use the $k$ source language models to estimate the parameters of a Gaussian prior for learning new POS taggers. This leads to significantly better performance in multi-source transfer set-ups. We also present a drop-out version that injects (empirical) Gaussian noise during online learning. Finally, we note that using empirical Gaussian priors leads to much lower Rademacher complexity, and is superior to optimally weighted model interpolation.

##### Abstract (translated by Google)
序列模型学习算法通常最大化对数似然减去模型的范数（或最小化海明损失+范数）。在跨语言词性标注（POS）中，我们的目标语言训练数据由一系列句子组成，这些句子由$ k $语言的翻译词汇标注，并通过词对齐标注数据。因此，我们的训练数据非常嘈杂，而且如果Rademacher的复杂度很高，学习算法很容易出现过度拟合。基于范数的正则化假定宽度为零，平均值为零。相反，我们建议使用$ k $源语言模型来估计学习新POS机的高斯先验参数。这导致在多源传输设置中显着更好的性能。我们还提供了一个在线学习期间注入（经验）高斯噪声的退出版本。最后，我们注意到，使用经验高斯先验导致更低的Rademacher复杂性，并且优于最佳加权模型内插。

##### URL
[https://arxiv.org/abs/1601.02166](https://arxiv.org/abs/1601.02166)

##### PDF
[https://arxiv.org/pdf/1601.02166](https://arxiv.org/pdf/1601.02166)

