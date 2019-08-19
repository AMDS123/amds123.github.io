---
layout: post
title: "The Angel is in the Priors: Improving GAN based Image and Sequence Inpainting with Better Noise and Structural Priors"
date: 2019-08-16 06:30:40
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Optimization Inference Deep_Learning
author: Avisek Lahiri, Arnav Kumar Jain, Prabir Kumar Biswas
mathjax: true
---

* content
{:toc}

##### Abstract
Contemporary deep learning based inpainting algorithms are mainly based on a hybrid dual stage training policy of supervised reconstruction loss followed by an unsupervised adversarial critic loss. However, there is a dearth of literature for a fully unsupervised GAN based inpainting framework. The primary aversion towards the latter genre is due to its prohibitively slow iterative optimization requirement during inference to find a matching noise prior for a masked image. In this paper, we show that priors matter in GAN: we learn a data driven parametric network to predict a matching prior for a given image. This converts an iterative paradigm to a single feed forward inference pipeline with a massive 1500X speedup and simultaneous improvement in reconstruction quality. We show that an additional structural prior imposed on GAN model results in higher fidelity outputs. To extend our model for sequence inpainting, we propose a recurrent net based grouped noise prior learning. To our knowledge, this is the first demonstration of an unsupervised GAN based sequence inpainting. A further improvement in sequence inpainting is achieved with an additional subsequence consistency loss. These contributions improve the spatio-temporal characteristics of reconstructed sequences. Extensive experiments conducted on SVHN, Standford Cars, CelebA and CelebA-HQ image datasets, synthetic sequences and ViDTIMIT video datasets reveal that we consistently improve upon previous unsupervised baseline and also achieve comparable performances(sometimes also better) to hybrid benchmarks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05861](https://arxiv.org/abs/1908.05861)

##### PDF
[https://arxiv.org/pdf/1908.05861](https://arxiv.org/pdf/1908.05861)

