---
layout: post
title: "An Improved Self-supervised GAN via Adversarial Training"
date: 2019-05-14 09:05:35
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification
author: Ngoc-Trung Tran, Viet-Hung Tran, Ngoc-Bao Nguyen, Ngai-Man Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to improve unconditional Generative Adversarial Networks (GAN) by training the self-supervised learning with the adversarial process. In particular, we apply self-supervised learning via the geometric transformation on input images and assign the pseudo-labels to these transformed images. (i) In addition to the GAN task, which distinguishes data (real) versus generated (fake) samples, we train the discriminator to predict the correct pseudo-labels of real transformed samples (classification task). Importantly, we find out that simultaneously training the discriminator to classify the fake class from the pseudo-classes of real samples for the classification task will improve the discriminator and subsequently lead better guides to train generator. (ii) The generator is trained by attempting to confuse the discriminator for not only the GAN task but also the classification task. For the classification task, the generator tries to confuse the discriminator recognizing the transformation of its output as one of the real transformed classes. Especially, we exploit that when the generator creates samples that result in a similar loss (via cross-entropy) as that of the real ones, the training is more stable and the generator distribution tends to match better the data distribution. When integrating our techniques into a state-of-the-art Auto-Encoder (AE) based-GAN model, they help to significantly boost the model's performance and also establish new state-of-the-art Fréchet Inception Distance (FID) scores in the literature of unconditional GAN for CIFAR-10 and STL-10 datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05469](https://arxiv.org/abs/1905.05469)

##### PDF
[https://arxiv.org/pdf/1905.05469](https://arxiv.org/pdf/1905.05469)

