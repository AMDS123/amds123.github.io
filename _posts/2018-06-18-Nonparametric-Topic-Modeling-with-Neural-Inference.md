---
layout: post
title: "Nonparametric Topic Modeling with Neural Inference"
date: 2018-06-18 10:22:18
categories: arXiv_CL
tags: arXiv_CL GAN Inference
author: Xuefei Ning, Yin Zheng, Zhuxi Jiang, Yu Wang, Huazhong Yang, Junzhou Huang
mathjax: true
---

* content
{:toc}

##### Abstract
This work focuses on combining nonparametric topic models with Auto-Encoding Variational Bayes (AEVB). Specifically, we first propose iTM-VAE, where the topics are treated as trainable parameters and the document-specific topic proportions are obtained by a stick-breaking construction. The inference of iTM-VAE is modeled by neural networks such that it can be computed in a simple feed-forward manner. We also describe how to introduce a hyper-prior into iTM-VAE so as to model the uncertainty of the prior parameter. Actually, the hyper-prior technique is quite general and we show that it can be applied to other AEVB based models to alleviate the {\it collapse-to-prior} problem elegantly. Moreover, we also propose HiTM-VAE, where the document-specific topic distributions are generated in a hierarchical manner. HiTM-VAE is even more flexible and can generate topic distributions with better variability. Experimental results on 20News and Reuters RCV1-V2 datasets show that the proposed models outperform the state-of-the-art baselines significantly. The advantages of the hyper-prior technique and the hierarchical model construction are also confirmed by experiments.

##### Abstract (translated by Google)
本工作重点将非参数主题模型与自动编码变分贝叶斯（AEVB）相结合。具体来说，我们首先提出iTM-VAE，其中的主题被视为可训练参数，文档特定的主题比例是通过坚持打破的结构获得的。 iTM-VAE的推断由神经网络建模，可以用简单的前馈方式进行计算。我们还描述了如何在iTM-VAE中引入超先验，以便对先验参数的不确定性进行建模。事实上，超先验技术是相当普遍的，我们表明它可以应用于其他基于AEVB的模型，以优雅地缓解{\ it折叠到先验}问题。此外，我们还提出了HiTM-VAE，其中文档特定的主题分布是以分层方式生成的。 HiTM-VAE更加灵活，可以生成具有更好变异性的主题分布。 20News和路透社RCV1-V2数据集的实验结果表明，所提出的模型显着优于最先进的基线。超现实技术和分层模型构造的优点也由实验证实。

##### URL
[http://arxiv.org/abs/1806.06583](http://arxiv.org/abs/1806.06583)

##### PDF
[http://arxiv.org/pdf/1806.06583](http://arxiv.org/pdf/1806.06583)

