---
layout: post
title: "GANFIT: Generative Adversarial Network Fitting for High Fidelity 3D Face Reconstruction"
date: 2019-02-15 19:53:45
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Face CNN Optimization Relation
author: Baris Gecer, Stylianos Ploumpis, Irene Kotsia, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
In the past few years, a lot of work has been done towards reconstructing the 3D facial structure from single images by capitalizing on the power of Deep Convolutional Neural Networks (DCNNs). In the most recent works, differentiable renderers were employed in order to learn the relationship between the facial identity features and the parameters of a 3D morphable model for shape and texture. The texture features either correspond to components of a linear texture space or are learned by auto-encoders directly from in-the-wild images. In all cases, the quality of the facial texture reconstruction of the state-of-the-art methods is still not capable of modelling textures in high fidelity. In this paper, we take a radically different approach and harness the power of Generative Adversarial Networks (GANs) and DCNNs in order to reconstruct the facial texture and shape from single images. That is, we utilize GANs to train a very powerful generator of facial texture in UV space. Then, we revisit the original 3D Morphable Models (3DMMs) fitting approaches making use of non-linear optimization to find the optimal latent parameters that best reconstruct the test image but under a new perspective. We optimize the parameters with the supervision of pretrained deep identity features through our end-to-end differentiable framework. We demonstrate excellent results in photorealistic and identity preserving 3D face reconstructions and achieve for the first time, to the best of our knowledge, facial texture reconstruction with high-frequency details.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05978](http://arxiv.org/abs/1902.05978)

##### PDF
[http://arxiv.org/pdf/1902.05978](http://arxiv.org/pdf/1902.05978)

