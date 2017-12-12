---
layout: post
title: "Semi-supervised Learning with GANs: Manifold Invariance with Improved Inference"
date: 2017-12-05 18:34:17
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Inference
author: Abhishek Kumar, Prasanna Sattigeri, P. Thomas Fletcher
mathjax: true
---

* content
{:toc}

##### Abstract
Semi-supervised learning methods using Generative Adversarial Networks (GANs) have shown promising empirical success recently. Most of these methods use a shared discriminator/classifier which discriminates real examples from fake while also predicting the class label. Motivated by the ability of the GANs generator to capture the data manifold well, we propose to estimate the tangent space to the data manifold using GANs and employ it to inject invariances into the classifier. In the process, we propose enhancements over existing methods for learning the inverse mapping (i.e., the encoder) which greatly improves in terms of semantic similarity of the reconstructed sample with the input sample. We observe considerable empirical gains in semi-supervised learning over baselines, particularly in the cases when the number of labeled examples is low. We also provide insights into how fake examples influence the semi-supervised learning procedure.

##### Abstract (translated by Google)
使用生成对抗网络（GAN）的半监督学习方法最近取得了有希望的经验成功。这些方法中的大多数使用共享的鉴别器/分类器，其将真实的例子与假的鉴别，同时也预测类别标签。 GANs生成器捕获数据流形的能力促使我们提出使用GAN估计数据流形的切空间，并用它将不变性注入到分类器中。在这个过程中，我们提出了比已有的用于学习逆映射（即，编码器）的方法的增强，其在重构样本与输入样本的语义相似性方面大大改进。我们观察到相对于基线的半监督学习的相当多的经验收益，特别是在标记的例子数量较少的情况下。我们还提供了如何假实例影响半监督学习过程的见解。

##### URL
[https://arxiv.org/abs/1705.08850](https://arxiv.org/abs/1705.08850)

##### PDF
[https://arxiv.org/pdf/1705.08850](https://arxiv.org/pdf/1705.08850)

