---
layout: post
title: "Gaussian Mixture Generative Adversarial Networks for Diverse Datasets, and the Unsupervised Clustering of Images"
date: 2018-08-30 15:32:40
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Matan Ben-Yosef, Daphna Weinshall
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have been shown to produce realistically looking synthetic images with remarkable success, yet their performance seems less impressive when the training set is highly diverse. In order to provide a better fit to the target data distribution when the dataset includes many different classes, we propose a variant of the basic GAN model, called Gaussian Mixture GAN (GM-GAN), where the probability distribution over the latent space is a mixture of Gaussians. We also propose a supervised variant which is capable of conditional sample synthesis. In order to evaluate the model's performance, we propose a new scoring method which separately takes into account two (typically conflicting) measures - diversity vs. quality of the generated data. Through a series of empirical experiments, using both synthetic and real-world datasets, we quantitatively show that GM-GANs outperform baselines, both when evaluated using the commonly used Inception Score, and when evaluated using our own alternative scoring method. In addition, we qualitatively demonstrate how the \textit{unsupervised} variant of GM-GAN tends to map latent vectors sampled from different Gaussians in the latent space to samples of different classes in the data space. We show how this phenomenon can be exploited for the task of unsupervised clustering, and provide quantitative evaluation showing the superiority of our method for the unsupervised clustering of image datasets. Finally, we demonstrate a feature which further sets our model apart from other GAN models: the option to control the quality-diversity trade-off by altering, post-training, the probability distribution of the latent space. This allows one to sample higher quality and lower diversity samples, or vice versa, according to one's needs.

##### Abstract (translated by Google)
生成性对抗网络（GAN）已经被证明可以产生逼真的合成图像并取得显着的成功，但是当训练集高度多样化时，它们的表现似乎不那么令人印象深刻。为了在数据集包含许多不同的类时更好地适应目标数据分布，我们提出了基本GAN模型的变体，称为高斯混合GAN（GM-GAN），其中潜在空间上的概率分布是高斯混合物。我们还提出了一种能够进行条件样品合成的监督变体。为了评估模型的性能，我们提出了一种新的评分方法，该方法分别考虑了两种（通常是相互冲突的）度量 - 生成数据的多样性与质量。通过一系列经验实验，使用合成数据集和真实数据集，我们定量地显示GM-GAN优于基线，无论是使用常用的初始评分进行评估，还是使用我们自己的替代评分方法进行评估。此外，我们定性地演示了GM-GAN的\ textit {无监督}变体如何将从潜在空间中的不同高斯采样的潜在向量映射到数据空间中不同类的样本。我们展示了这种现象如何被用于无监督聚类的任务，并提供定量评估，显示我们的方法对无监督聚类的图像数据集的优越性。最后，我们展示了一个特征，它进一步将我们的模型与其他GAN模型区分开来：通过改变，训练后，潜在空间的概率分布来控制质量 - 多样性权衡的选项。这允许人们根据一个人的需要对更高质量和更低分集的样本进行采样，反之亦然。

##### URL
[http://arxiv.org/abs/1808.10356](http://arxiv.org/abs/1808.10356)

##### PDF
[http://arxiv.org/pdf/1808.10356](http://arxiv.org/pdf/1808.10356)

