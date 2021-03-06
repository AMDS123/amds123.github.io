---
layout: post
title: "Point Cloud GAN"
date: 2018-10-13 04:14:14
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Inference Recognition
author: Chun-Liang Li, Manzil Zaheer, Yang Zhang, Barnabas Poczos, Ruslan Salakhutdinov
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GAN) can achieve promising performance on learning complex data distributions on different types of data. In this paper, we first show a straightforward extension of existing GAN algorithm is not applicable to point clouds, because the constraint required for discriminators is undefined for set data. We propose a two fold modification to GAN algorithm for learning to generate point clouds (PC-GAN). First, we combine ideas from hierarchical Bayesian modeling and implicit generative models by learning a hierarchical and interpretable sampling process. A key component of our method is that we train a posterior inference network for the hidden variables. Second, instead of using only state-of-the-art Wasserstein GAN objective, we propose a sandwiching objective, which results in a tighter Wasserstein distance estimate than the commonly used dual form. Thereby, PC-GAN defines a generic framework that can incorporate many existing GAN algorithms. We validate our claims on ModelNet40 benchmark dataset. Using the distance between generated point clouds and true meshes as metric, we find that PC-GAN trained by the sandwiching objective achieves better results on test data than the existing methods. Moreover, as a byproduct, PC- GAN learns versatile latent representations of point clouds, which can achieve competitive performance with other unsupervised learning algorithms on object recognition task. Lastly, we also provide studies on generating unseen classes of objects and transforming image to point cloud, which demonstrates the compelling generalization capability and potentials of PC-GAN.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05795](https://arxiv.org/abs/1810.05795)

##### PDF
[https://arxiv.org/pdf/1810.05795](https://arxiv.org/pdf/1810.05795)

