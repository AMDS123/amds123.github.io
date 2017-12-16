---
layout: post
title: "DeepCoder: Semi-parametric Variational Autoencoders for Automatic Facial Action Coding"
date: 2017-08-05 04:26:08
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Deep_Learning
author: Dieu Linh Tran, Robert Walecki, Ognjen Rudovic, Stefanos Eleftheriadis, Bjørn Schuller, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
Human face exhibits an inherent hierarchy in its representations (i.e., holistic facial expressions can be encoded via a set of facial action units (AUs) and their intensity). Variational (deep) auto-encoders (VAE) have shown great results in unsupervised extraction of hierarchical latent representations from large amounts of image data, while being robust to noise and other undesired artifacts. Potentially, this makes VAEs a suitable approach for learning facial features for AU intensity estimation. Yet, most existing VAE-based methods apply classifiers learned separately from the encoded features. By contrast, the non-parametric (probabilistic) approaches, such as Gaussian Processes (GPs), typically outperform their parametric counterparts, but cannot deal easily with large amounts of data. To this end, we propose a novel VAE semi-parametric modeling framework, named DeepCoder, which combines the modeling power of parametric (convolutional) and nonparametric (ordinal GPs) VAEs, for joint learning of (1) latent representations at multiple levels in a task hierarchy1, and (2) classification of multiple ordinal outputs. We show on benchmark datasets for AU intensity estimation that the proposed DeepCoder outperforms the state-of-the-art approaches, and related VAEs and deep learning models.

##### Abstract (translated by Google)
人脸在其表示中表现出固有的等级（即，整体面部表情可以通过一组面部动作单元（AU）及其强度来编码）。变分（深）自动编码器（VAE）在无监督地从大量图像数据中提取分层隐式表示方面显示出了很好的结果，同时对噪声和其他不希望的伪像也是鲁棒的。有可能，这使得VAE成为AU强度估计的一种适合于学习面部特征的方法。然而，大多数现有的基于VAE的方法应用分类器，这些分类器是从编码特征中分别学习的相比之下，诸如高斯过程（GPs）的非参数（概率）方法通常优于其参数对应方法，但是不能容易地处理大量的数据。为此，我们提出了一个新的VAE半参数建模框架，名为DeepCoder，它结合了参数（卷积）和非参数（序数GPs）VAE的建模能力，用于联合学习（1）多层次的潜在表示任务层次1，以及（2）多个序数输出的分类。我们在基准数据集上展示了AU强度估计，所提出的DeepCoder优于最先进的方法，以及相关的VAE和深度学习模型。

##### URL
[https://arxiv.org/abs/1704.02206](https://arxiv.org/abs/1704.02206)

##### PDF
[https://arxiv.org/pdf/1704.02206](https://arxiv.org/pdf/1704.02206)

