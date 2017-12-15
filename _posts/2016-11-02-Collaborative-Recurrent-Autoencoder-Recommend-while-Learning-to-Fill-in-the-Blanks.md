---
layout: post
title: "Collaborative Recurrent Autoencoder: Recommend while Learning to Fill in the Blanks"
date: 2016-11-02 02:49:44
categories: arXiv_CL
tags: arXiv_CL Deep_Learning Recommendation
author: Hao Wang, Xingjian Shi, Dit-Yan Yeung
mathjax: true
---

* content
{:toc}

##### Abstract
Hybrid methods that utilize both content and rating information are commonly used in many recommender systems. However, most of them use either handcrafted features or the bag-of-words representation as a surrogate for the content information but they are neither effective nor natural enough. To address this problem, we develop a collaborative recurrent autoencoder (CRAE) which is a denoising recurrent autoencoder (DRAE) that models the generation of content sequences in the collaborative filtering (CF) setting. The model generalizes recent advances in recurrent deep learning from i.i.d. input to non-i.i.d. (CF-based) input and provides a new denoising scheme along with a novel learnable pooling scheme for the recurrent autoencoder. To do this, we first develop a hierarchical Bayesian model for the DRAE and then generalize it to the CF setting. The synergy between denoising and CF enables CRAE to make accurate recommendations while learning to fill in the blanks in sequences. Experiments on real-world datasets from different domains (CiteULike and Netflix) show that, by jointly modeling the order-aware generation of sequences for the content information and performing CF for the ratings, CRAE is able to significantly outperform the state of the art on both the recommendation task based on ratings and the sequence generation task based on content information.

##### Abstract (translated by Google)
利用内容和评分信息的混合方法通常用于许多推荐系统。然而，他们大多使用手工制作的特征或者文字表示来代替内容信息，但是它们既不够有效，也不够自然。为了解决这个问题，我们开发了一种协作循环自动编码器（CRAE），它是一种去噪复发自动编码器（DRAE），它在协同过滤（CF）设置中对内容序列的生成进行建模。该模型概括了从i.i.d.中反复深入学习的最新进展。输入到非i.i.d。 （基于CF）的输入，并且提供了新的去噪方案以及用于经常性自动编码器的新颖的可学习汇集方案。为此，我们首先为DRAE开发一个分层贝叶斯模型，然后将其推广到CF设置。去噪和CF之间的协同作用使得CRAE能够在学习按顺序填充空白的同时提供准确的建议。来自不同领域（CiteULike和Netflix）的实际数据集的实验表明，通过联合建模内容信息的序列感知序列生成和执行评级的CF，CRAE能够显着地超越目前的技术水平基于评级的推荐任务和基于内容信息的序列生成任务。

##### URL
[https://arxiv.org/abs/1611.00454](https://arxiv.org/abs/1611.00454)

##### PDF
[https://arxiv.org/pdf/1611.00454](https://arxiv.org/pdf/1611.00454)

