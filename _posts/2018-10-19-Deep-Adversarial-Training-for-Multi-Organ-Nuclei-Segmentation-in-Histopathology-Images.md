---
layout: post
title: "Deep Adversarial Training for Multi-Organ Nuclei Segmentation in Histopathology Images"
date: 2018-10-19 20:59:31
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Classification Deep_Learning Prediction
author: Faisal Mahmood, Daniel Borders, Richard Chen, Gregory N. McKay, Kevan J. Salimian, Alexander Baras, Nicholas J. Durr
mathjax: true
---

* content
{:toc}

##### Abstract
Nuclei segmentation is a fundamental task that is critical for various computational pathology applications including nuclei morphology analysis, cell type classification, and cancer grading. Conventional vision-based methods for nuclei segmentation struggle in challenging cases and deep learning approaches have proven to be more robust and generalizable. However, CNNs require large amounts of labeled histopathology data. Moreover, conventional CNN-based approaches lack structured prediction capabilities which are required to distinguish overlapping and clumped nuclei. Here, we present an approach to nuclei segmentation that overcomes these challenges by utilizing a conditional generative adversarial network (cGAN) trained with synthetic and real data. We generate a large dataset of H&amp;E training images with perfect nuclei segmentation labels using an unpaired GAN framework. This synthetic data along with real histopathology data from six different organs are used to train a conditional GAN with spectral normalization and gradient penalty for nuclei segmentation. This adversarial regression framework enforces higher order consistency when compared to conventional CNN models. We demonstrate that this nuclei segmentation approach generalizes across different organs, sites, patients and disease states, and outperforms conventional approaches, especially in isolating individual and overlapping nuclei.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.00236](http://arxiv.org/abs/1810.00236)

##### PDF
[http://arxiv.org/pdf/1810.00236](http://arxiv.org/pdf/1810.00236)

