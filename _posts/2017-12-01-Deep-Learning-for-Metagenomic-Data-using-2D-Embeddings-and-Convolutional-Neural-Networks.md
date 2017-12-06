---
layout: post
title: "Deep Learning for Metagenomic Data: using 2D Embeddings and Convolutional Neural Networks"
date: 2017-12-01 09:18:04
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Thanh Hai Nguyen, Yann Chevaleyre, Edi Prifti, Nataliya Sokolovska, Jean-Daniel Zucker
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning (DL) techniques have had unprecedented success when applied to images, waveforms, and texts to cite a few. In general, when the sample size (N) is much greater than the number of features (d), DL outperforms previous machine learning (ML) techniques, often through the use of convolution neural networks (CNNs). However, in many bioinformatics ML tasks, we encounter the opposite situation where d is greater than N. In these situations, applying DL techniques (such as feed-forward networks) would lead to severe overfitting. Thus, sparse ML techniques (such as LASSO e.g.) usually yield the best results on these tasks. In this paper, we show how to apply CNNs on data which do not have originally an image structure (in particular on metagenomic data). Our first contribution is to show how to map metagenomic data in a meaningful way to 1D or 2D images. Based on this representation, we then apply a CNN, with the aim of predicting various diseases. The proposed approach is applied on six different datasets including in total over 1000 samples from various diseases. This approach could be a promising one for prediction tasks in the bioinformatics field.

##### Abstract (translated by Google)
深度学习（DL）技术在应用于图像，波形和文本等方面已经取得了前所未有的成功。一般来说，当样本大小（N）比特征数量（d）大得多时，DL通常通过使用卷积神经网络（CNN）而胜过先前的机器学习（ML）技术。然而，在许多生物信息学ML任务中，我们遇到d大于N的相反情况。在这些情况下，应用DL技术（例如前馈网络）将导致严重的过拟合。因此，稀疏的ML技术（例如LASSO）通常对这些任务产生最好的结果。在本文中，我们将演示如何将CNN应用于原本没有图像结构（特别是宏基因组数据）的数据。我们的第一个贡献是展示如何以有意义的方式将宏基因组数据映射到一维或二维图像。基于这种表示，我们然后申请CNN，以预测各种疾病的目的。所提出的方法适用于六个不同的数据集，包括来自各种疾病的总共1000多个样本。这种方法对于生物信息学领域的预测任务可能是有前景的。

##### URL
[https://arxiv.org/abs/1712.00244](https://arxiv.org/abs/1712.00244)

