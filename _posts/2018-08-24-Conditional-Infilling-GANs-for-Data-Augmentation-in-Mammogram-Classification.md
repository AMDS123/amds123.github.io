---
layout: post
title: "Conditional Infilling GANs for Data Augmentation in Mammogram Classification"
date: 2018-08-24 16:57:16
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification Deep_Learning Detection
author: Eric Wu, Kevin Wu, David Cox, William Lotter
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning approaches to breast cancer detection in mammograms have recently shown promising results. However, such models are constrained by the limited size of publicly available mammography datasets, in large part due to privacy concerns and the high cost of generating expert annotations. Limited dataset size is further exacerbated by substantial class imbalance since "normal" images dramatically outnumber those with findings. Given the rapid progress of generative models in synthesizing realistic images, and the known effectiveness of simple data augmentation techniques (e.g. horizontal flipping), we ask if it is possible to synthetically augment mammogram datasets using generative adversarial networks (GANs). We train a class-conditional GAN to perform contextual in-filling, which we then use to synthesize lesions onto healthy screening mammograms. First, we show that GANs are capable of generating high-resolution synthetic mammogram patches. Next, we experimentally evaluate using the augmented dataset to improve breast cancer classification performance. We observe that a ResNet-50 classifier trained with GAN-augmented training data produces a higher AUROC compared to the same model trained only on traditionally augmented data, demonstrating the potential of our approach.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.08093](https://arxiv.org/abs/1807.08093)

##### PDF
[https://arxiv.org/pdf/1807.08093](https://arxiv.org/pdf/1807.08093)

