---
layout: post
title: "Riemannian Normalizing Flow on Variational Wasserstein Autoencoder for Text Modeling"
date: 2019-04-04 08:13:42
categories: arXiv_CL
tags: arXiv_CL Face Text_Generation Optimization Language_Model
author: Prince Zizhuang Wang, William Yang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Variational Autoencoder has been widely used for language modeling and text generation tasks. These models often face a difficult optimization problem, also known as the Kullback-Leibler (KL) term vanishing issue, where the posterior easily collapses to the prior, and the model will ignore latent codes in generative tasks. To address this problem, we introduce an improved Wasserstein Variational Autoencoder (WAE) with Riemannian Normalizing Flow (RNF) for text modeling. The RNF transforms a latent variable into a space that respects the geometric characteristics of input space, which makes posterior impossible to collapse to the non-informative prior. The Wasserstein objective minimizes the distance between the marginal distribution and the prior directly and therefore does not force the posterior to match the prior. Empirical experiments show that our model avoids KL vanishing over a range of datasets and has better performances in tasks such as language modeling, likelihood approximation, and text generation. Through a series of experiments and analysis over latent space, we show that our model learns latent distributions that respect latent space geometry and is able to generate sentences that are more diverse.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02399](http://arxiv.org/abs/1904.02399)

##### PDF
[http://arxiv.org/pdf/1904.02399](http://arxiv.org/pdf/1904.02399)

