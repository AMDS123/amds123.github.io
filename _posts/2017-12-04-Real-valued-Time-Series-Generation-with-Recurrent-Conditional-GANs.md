---
layout: post
title: "Real-valued Time Series Generation with Recurrent Conditional GANs"
date: 2017-12-04 04:31:38
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN RNN Classification Quantitative
author: Cristóbal Esteban, Stephanie L. Hyland, Gunnar Rätsch
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have shown remarkable success as a framework for training models to produce realistic-looking data. In this work, we propose a Recurrent GAN (RGAN) and Recurrent Conditional GAN (RCGAN) to produce realistic real-valued multi-dimensional time series, with an emphasis on their application to medical data. RGANs make use of recurrent neural networks in the generator and the discriminator. In the case of RCGANs, both of these RNNs are conditioned on auxiliary information. We demonstrate our models in a set of toy datasets, where we show visually and quantitatively (using sample likelihood and maximum mean discrepancy) that they can successfully generate realistic time-series. We also describe novel evaluation methods for GANs, where we generate a synthetic labelled training dataset, and evaluate on a real test set the performance of a model trained on the synthetic data, and vice-versa. We illustrate with these metrics that RCGANs can generate time-series data useful for supervised training, with only minor degradation in performance on real test data. This is demonstrated on digit classification from 'serialised' MNIST and by training an early warning system on a medical dataset of 17,000 patients from an intensive care unit. We further discuss and analyse the privacy concerns that may arise when using RCGANs to generate realistic synthetic medical time series data.

##### Abstract (translated by Google)
生成对抗网络（GANs）作为训练模型来生成逼真数据的框架已经取得了显着的成功。在这项工作中，我们提出一个复发GAN（RGAN）和复发条件GAN（RCGAN）来产生逼真的实值多维时间序列，重点是它们在医疗数据中的应用。 RGAN利用发生器和鉴别器中的递归神经网络。在RCGAN的情况下，这两个RNN都以辅助信息为条件。我们在一组玩具数据集中展示了我们的模型，在这些数据集中，我们直观和定量地显示（使用样本可能性和最大平均差异），他们可以成功生成逼真的时间序列。我们还描述了GAN的新的评估方法，我们生成一个合成标记的训练数据集，并在一个真实的测试集上评估在合成数据上训练的模型的性能，反之亦然。我们用这些度量来说明，RCGAN可以生成对监督训练有用的时间序列数据，而在实际测试数据上只有很小的性能下降。这从“序列化”MNIST的数字分类以及通过训练来自重症监护病房的17,000名患者的医学数据集上的预警系统来证明。我们进一步讨论和分析使用RCGAN生成逼真的合成医学时间序列数据时可能出现的隐私问题。

##### URL
[https://arxiv.org/abs/1706.02633](https://arxiv.org/abs/1706.02633)

##### PDF
[https://arxiv.org/pdf/1706.02633](https://arxiv.org/pdf/1706.02633)

