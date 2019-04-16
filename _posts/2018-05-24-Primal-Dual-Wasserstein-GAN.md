---
layout: post
title: "Primal-Dual Wasserstein GAN"
date: 2018-05-24 09:47:16
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Inference
author: Mevlana Gemici, Zeynep Akata, Max Welling
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Primal-Dual Wasserstein GAN, a new learning algorithm for building latent variable models of the data distribution based on the primal and the dual formulations of the optimal transport (OT) problem. We utilize the primal formulation to learn a flexible inference mechanism and to create an optimal approximate coupling between the data distribution and the generative model. In order to learn the generative model, we use the dual formulation and train the decoder adversarially through a critic network that is regularized by the approximate coupling obtained from the primal. Unlike previous methods that violate various properties of the optimal critic, we regularize the norm and the direction of the gradients of the critic function. Our model shares many of the desirable properties of auto-encoding models in terms of mode coverage and latent structure, while avoiding their undesirable averaging properties, e.g. their inability to capture sharp visual features when modeling real images. We compare our algorithm with several other generative modeling techniques that utilize Wasserstein distances on Frechet Inception Distance (FID) and Inception Scores (IS).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.09575](https://arxiv.org/abs/1805.09575)

##### PDF
[https://arxiv.org/pdf/1805.09575](https://arxiv.org/pdf/1805.09575)

