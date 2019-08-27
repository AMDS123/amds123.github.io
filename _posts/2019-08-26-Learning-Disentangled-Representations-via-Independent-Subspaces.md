---
layout: post
title: "Learning Disentangled Representations via Independent Subspaces"
date: 2019-08-26 09:08:12
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Semantic_Segmentation
author: Maren Awiszus, Hanno Ackermann, Bodo Rosenhahn
mathjax: true
---

* content
{:toc}

##### Abstract
Image generating neural networks are mostly viewed as black boxes, where any change in the input can have a number of globally effective changes on the output. In this work, we propose a method for learning disentangled representations to allow for localized image manipulations. We use face images as our example of choice. Depending on the image region, identity and other facial attributes can be modified. The proposed network can transfer parts of a face such as shape and color of eyes, hair, mouth, etc.~directly between persons while all other parts of the face remain unchanged. The network allows to generate modified images which appear like realistic images. Our model learns disentangled representations by weak supervision. We propose a localized resnet autoencoder optimized using several loss functions including a loss based on the semantic segmentation, which we interpret as masks, and a loss which enforces disentanglement by decomposition of the latent space into statistically independent subspaces. We evaluate the proposed solution w.r.t. disentanglement and generated image quality. Convincing results are demonstrated using the CelebA dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08989](http://arxiv.org/abs/1908.08989)

##### PDF
[http://arxiv.org/pdf/1908.08989](http://arxiv.org/pdf/1908.08989)

