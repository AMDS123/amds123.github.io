---
layout: post
title: "Sharing deep generative representation for perceived image reconstruction from human brain activity"
date: 2017-07-11 01:50:34
categories: arXiv_CV
tags: arXiv_CV Regularization Attention Inference Classification Prediction Relation
author: Changde Du, Changying Du, Huiguang He
mathjax: true
---

* content
{:toc}

##### Abstract
Decoding human brain activities via functional magnetic resonance imaging (fMRI) has gained increasing attention in recent years. While encouraging results have been reported in brain states classification tasks, reconstructing the details of human visual experience still remains difficult. Two main challenges that hinder the development of effective models are the perplexing fMRI measurement noise and the high dimensionality of limited data instances. Existing methods generally suffer from one or both of these issues and yield dissatisfactory results. In this paper, we tackle this problem by casting the reconstruction of visual stimulus as the Bayesian inference of missing view in a multiview latent variable model. Sharing a common latent representation, our joint generative model of external stimulus and brain response is not only "deep" in extracting nonlinear features from visual images, but also powerful in capturing correlations among voxel activities of fMRI recordings. The nonlinearity and deep structure endow our model with strong representation ability, while the correlations of voxel activities are critical for suppressing noise and improving prediction. We devise an efficient variational Bayesian method to infer the latent variables and the model parameters. To further improve the reconstruction accuracy, the latent representations of testing instances are enforced to be close to that of their neighbours from the training set via posterior regularization. Experiments on three fMRI recording datasets demonstrate that our approach can more accurately reconstruct visual stimuli.

##### Abstract (translated by Google)
通过功能磁共振成像（fMRI）解码人脑活动近年来受到越来越多的关注。尽管在大脑状态分类任务中已经报告了令人鼓舞的结果，但重建人类视觉体验的细节仍然是困难的。阻碍有效模型发展的两个主要挑战是功能磁共振成像测量噪音的复杂性和有限数据实例的高维度。现有的方法通常遭受这些问题中的一个或两个，并产生不令人满意的结果。在本文中，我们通过将视觉刺激的重建作为多视图潜变量模型中的缺失视图的贝叶斯推断来解决这个问题。共享一个共同的潜在表示，我们的外部刺激和大脑反应的联合生成模型不仅从视觉图像中提取非线性特征“深”，而且在捕获fMRI记录的体素活动之间的相关性方面也是强大的。非线性和深层结构使我们的模型具有较强的表示能力，而体素活动的相关性对于抑制噪声和改进预测至关重要。我们设计一个有效的变分贝叶斯方法来推断潜变量和模型参数。为了进一步提高重构的准确性，通过后验正则化，将测试用例的潜在表示强度从训练集中逼近到邻居。三个功能磁共振成像记录数据集的实验表明，我们的方法可以更准确地重建视觉刺激。

##### URL
[https://arxiv.org/abs/1704.07575](https://arxiv.org/abs/1704.07575)

##### PDF
[https://arxiv.org/pdf/1704.07575](https://arxiv.org/pdf/1704.07575)

