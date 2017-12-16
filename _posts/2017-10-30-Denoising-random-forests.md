---
layout: post
title: "Denoising random forests"
date: 2017-10-30 15:16:51
categories: arXiv_CV
tags: arXiv_CV
author: Masaya Hibino, Akisato Kimura, Takayoshi Yamashita, Yuji Yamauchi, Hironobu Fujiyoshi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel type of random forests called a denoising random forests that are robust against noises contained in test samples. Such noise-corrupted samples cause serious damage to the estimation performances of random forests, since unexpected child nodes are often selected and the leaf nodes that the input sample reaches are sometimes far from those for a clean sample. Our main idea for tackling this problem originates from a binary indicator vector that encodes a traversal path of a sample in the forest. Our proposed method effectively employs this vector by introducing denoising autoencoders into random forests. A denoising autoencoder can be trained with indicator vectors produced from clean and noisy input samples, and non-leaf nodes where incorrect decisions are made can be identified by comparing the input and output of the trained denoising autoencoder. Multiple traversal paths with respect to the nodes with incorrect decisions caused by the noises can then be considered for the estimation.

##### Abstract (translated by Google)
本文提出了一种新型随机森林，称为去噪随机森林，对测试样本中包含的噪声具有很强的抵抗力。这样噪声破坏的样本会对随机森林的估计性能造成严重损害，因为经常选择意外的子节点，并且输入样本到达的叶节点有时远离那些干净的样本。我们解决这个问题的主要思想源于二进制指标向量，它编码森林中样本的遍历路径。我们提出的方法有效地利用这个向量通过引入去噪自动编码器到随机森林。去噪自动编码器可以利用从干净的和有噪声的输入样本产生的指示向量来训练，并且可以通过比较训练的去噪自动编码器的输入和输出来识别做出不正确决定的非叶节点。然后可以考虑针对由噪声引起的具有不正确决定的节点的多个遍历路径进行估计。

##### URL
[https://arxiv.org/abs/1710.11004](https://arxiv.org/abs/1710.11004)

##### PDF
[https://arxiv.org/pdf/1710.11004](https://arxiv.org/pdf/1710.11004)

