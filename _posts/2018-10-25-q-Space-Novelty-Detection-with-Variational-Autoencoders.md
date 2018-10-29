---
layout: post
title: "q-Space Novelty Detection with Variational Autoencoders"
date: 2018-10-25 17:34:51
categories: arXiv_AI
tags: arXiv_AI Detection
author: Aleksei Vasilev, Vladimir Golkov, Marc Meissner, Ilona Lipp, Eleonora Sgarlata, Valentina Tomassini, Derek K. Jones, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
In machine learning, novelty detection is the task of identifying novel unseen data. During training, only samples from the normal class are available. Test samples are classified as normal or abnormal by assignment of a novelty score. Here we propose novelty detection methods based on training variational autoencoders (VAEs) on normal data. Since abnormal samples are not used during training, we define novelty metrics based on the (partially complementary) assumptions that the VAE is less capable of reconstructing abnormal samples well; that abnormal samples more strongly violate the VAE regularizer; and that abnormal samples differ from normal samples not only in input-feature space, but also in the VAE latent space and VAE output. These approaches, combined with various possibilities of using (e.g. sampling) the probabilistic VAE to obtain scalar novelty scores, yield a large family of methods. We apply these methods to magnetic resonance imaging, namely to the detection of diffusion-space (q-space) abnormalities in diffusion MRI scans of multiple sclerosis patients, i.e. to detect multiple sclerosis lesions without using any lesion labels for training. Many of our methods outperform previously proposed q-space novelty detection methods. We also evaluate the proposed methods on the MNIST handwritten digits dataset and show that many of them are able to outperform the state of the art.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.02997](https://arxiv.org/abs/1806.02997)

##### PDF
[https://arxiv.org/pdf/1806.02997](https://arxiv.org/pdf/1806.02997)

