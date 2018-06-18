---
layout: post
title: "Scalable Factorized Hierarchical Variational Autoencoder Training"
date: 2018-06-15 04:25:16
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Optimization Inference Relation Recognition
author: Wei-Ning Hsu, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
Deep generative models have achieved great success in unsupervised learning with the ability to capture complex nonlinear relationships between latent generating factors and observations. Among them, a factorized hierarchical variational autoencoder (FHVAE) is a variational inference-based model that formulates a hierarchical generative process for sequential data. Specifically, an FHVAE model can learn disentangled and interpretable representations, which have been proven useful for numerous speech applications, such as speaker verification, robust speech recognition, and voice conversion. However, as we will elaborate in this paper, the training algorithm proposed in the original paper is not scalable to datasets of thousands of hours, which makes this model less applicable on a larger scale. After identifying limitations in terms of runtime, memory, and hyperparameter optimization, we propose a hierarchical sampling training algorithm to address all three issues. Our proposed method is evaluated comprehensively on a wide variety of datasets, ranging from 3 to 1,000 hours and involving different types of generating factors, such as recording conditions and noise types. In addition, we also present a new visualization method for qualitatively evaluating the performance with respect to the interpretability and disentanglement. Models trained with our proposed algorithm demonstrate the desired characteristics on all the datasets.

##### Abstract (translated by Google)
深度生成模型在无监督学习中取得了巨大成功，能够捕捉潜在生成因子与观测之间的复杂非线性关系。其中，分层分层变分自动编码器（FHVAE）是一种基于变分推理的模型，为顺序数据制定了分层生成过程。具体而言，FHVAE模型可以学习解开和可解释的表示，这些表示已被证明可用于许多语音应用，例如说话者验证，鲁棒语音识别和语音转换。然而，正如我们将在本文中详细阐述的那样，原始论文中提出的训练算法不可扩展到数千小时的数据集，这使得该模型不适用于更大规模。在识别运行时，内存和超参数优化方面的限制之后，我们提出了一种分层抽样训练算法来解决所有三个问题。我们提出的方法在广泛的数据集上进行了全面评估，范围从3到1,000小时，涉及不同类型的生成因素，例如记录条件和噪声类型。此外，我们还提出了一种新的可视化方法，用于定性评估关于解释性和解开性的表现。用我们提出的算法训练的模型在所有数据集上展示了所需的特性。

##### URL
[http://arxiv.org/abs/1804.03201](http://arxiv.org/abs/1804.03201)

##### PDF
[http://arxiv.org/pdf/1804.03201](http://arxiv.org/pdf/1804.03201)

