---
layout: post
title: "Coverage and Quality Driven Training of Generative Image Models"
date: 2019-01-04 13:43:18
categories: arXiv_CV
tags: arXiv_CV Adversarial Relation
author: Konstantin Shmelkov, Thomas Lucas, Karteek Alahari, Cordelia Schmid, Jakob Verbeek
mathjax: true
---

* content
{:toc}

##### Abstract
Generative modeling of natural images has been extensively studied in recent years, yielding remarkable progress. Current state-of-the-art methods are either based on maximum likelihood estimation or adversarial training. Both methods have their own drawbacks, which are complementary in nature. The first leads to over-generalization as the maximum likelihood criterion encourages models to cover the support of the training data by heavily penalizing small masses assigned to training data. Simplifying assumptions in such models limits their capacity and makes them spill mass on unrealistic samples. The second leads to mode-dropping since adversarial training encourages high quality samples from the model, but only indirectly enforces diversity among the samples. To overcome these drawbacks we make two contributions. First, we propose a novel extension to the variational autoencoders model by using deterministic invertible transformation layers to map samples from the decoder to the image space. This induces correlations among the pixels given the latent variables, improving over commonly used factorial decoders. Second, we propose a training approach that leverages coverage and quality based criteria. Our models obtain likelihood scores competitive with state-of-the-art likelihood-based models, while achieving sample quality typical of adversarially trained networks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.01091](https://arxiv.org/abs/1901.01091)

##### PDF
[https://arxiv.org/pdf/1901.01091](https://arxiv.org/pdf/1901.01091)

