---
layout: post
title: "Low-rank and Sparse Soft Targets to Learn Better DNN Acoustic Models"
date: 2016-10-18 16:02:10
categories: arXiv_CL
tags: arXiv_CL Sparse Speech_Recognition Recognition
author: Pranay Dighe, Afsaneh Asaei, Herve Bourlard
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional deep neural networks (DNN) for speech acoustic modeling rely on Gaussian mixture models (GMM) and hidden Markov model (HMM) to obtain binary class labels as the targets for DNN training. Subword classes in speech recognition systems correspond to context-dependent tied states or senones. The present work addresses some limitations of GMM-HMM senone alignments for DNN training. We hypothesize that the senone probabilities obtained from a DNN trained with binary labels can provide more accurate targets to learn better acoustic models. However, DNN outputs bear inaccuracies which are exhibited as high dimensional unstructured noise, whereas the informative components are structured and low-dimensional. We exploit principle component analysis (PCA) and sparse coding to characterize the senone subspaces. Enhanced probabilities obtained from low-rank and sparse reconstructions are used as soft-targets for DNN acoustic modeling, that also enables training with untranscribed data. Experiments conducted on AMI corpus shows 4.6% relative reduction in word error rate.

##### Abstract (translated by Google)
用于语音声学建模的常规深度神经网络（DNN）依靠高斯混合模型（GMM）和隐马尔可夫模型（HMM）来获得二元类标签作为DNN训练的目标。语音识别系统中的子字类对应于依赖于上下文的绑定状态或语音。目前的工作解决了一些DNM训练的GMM-HMM音序比对的局限性。我们假设从二元标签训练的DNN获得的句子概率可以提供更准确的目标来学习更好的声学模型。然而，DNN输出具有不确定性，表现为高维非结构化噪声，而信息组件是结构化和低维的。我们利用主成分分析（PCA）和稀疏编码来表征句子子空间。从低秩和稀疏重建获得的增强概率被用作DNN声学建模的软目标，这也使得能够训练未转录的数据。在AMI语料库上进行的实验显示，字错误率相对降低了4.6％。

##### URL
[https://arxiv.org/abs/1610.05688](https://arxiv.org/abs/1610.05688)

##### PDF
[https://arxiv.org/pdf/1610.05688](https://arxiv.org/pdf/1610.05688)

