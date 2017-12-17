---
layout: post
title: "Zero-Shot Learning via Class-Conditioned Deep Generative Models"
date: 2017-11-19 23:32:05
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Wenlin Wang, Yunchen Pu, Vinay Kumar Verma, Kai Fan, Yizhe Zhang, Changyou Chen, Piyush Rai, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep generative model for learning to predict classes not seen at training time. Unlike most existing methods for this problem, that represent each class as a point (via a semantic embedding), we represent each seen/unseen class using a class-specific latent-space distribution, conditioned on class attributes. We use these latent-space distributions as a prior for a supervised variational autoencoder (VAE), which also facilitates learning highly discriminative feature representations for the inputs. The entire framework is learned end-to-end using only the seen-class training data. The model infers corresponding attributes of a test image by maximizing the VAE lower bound; the inferred attributes may be linked to labels not seen when training. We further extend our model to a (1) semi-supervised/transductive setting by leveraging unlabeled unseen-class data via an unsupervised learning module, and (2) few-shot learning where we also have a small number of labeled inputs from the unseen classes. We compare our model with several state-of-the-art methods through a comprehensive set of experiments on a variety of benchmark data sets.

##### Abstract (translated by Google)
我们提出了一个深刻的生成模型来学习预测在培训时间没有看到的课程。与大多数现有的针对这个问题的方法不同，它们将每个类表示为一个点（通过语义嵌入），我们使用特定于类的潜在空间分布来表示每个可见/不可见的类，并以类属性为条件。我们使用这些潜在空间分布作为有监督的变分自动编码器（VAE）的先验，这也有助于为输入学习高度可区分的特征表示。整个框架是端对端地学习，只使用可见级别的训练数据。该模型通过最大化VAE下限来推断测试图像的相应属性;推断的属性可能与训练时未看到的标签相关联。我们进一步扩展我们的模型到一个（1）半监督/转导的设置，通过利用无标记的看不见的类数据通过一个无监督的学习模块，（2）少量学习，我们也有少量的标记输入类。我们通过对各种基准数据集进行全面的实验，将我们的模型与几种最先进的方法进行比较。

##### URL
[https://arxiv.org/abs/1711.05820](https://arxiv.org/abs/1711.05820)

##### PDF
[https://arxiv.org/pdf/1711.05820](https://arxiv.org/pdf/1711.05820)

