---
layout: post
title: "Variational Adversarial Active Learning"
date: 2019-03-31 09:54:17
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Image_Classification Semantic_Segmentation Classification
author: Samarth Sinha, Sayna Ebrahimi, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Active learning aims to develop label-efficient algorithms by sampling the most representative queries to be labeled by an oracle. We describe a pool-based semi-supervised active learning algorithm that implicitly learns this sampling mechanism in an adversarial manner. Our method learns a latent space using a variational autoencoder (VAE) and an adversarial network trained to discriminate between unlabeled and labeled data. The mini-max game between the VAE and the adversarial network is played such that while the VAE tries to trick the adversarial network into predicting that all data points are from the labeled pool, the adversarial network learns how to discriminate between dissimilarities in the latent space. We extensively evaluate our method on various image classification and semantic segmentation benchmark datasets and establish a new state of the art on $\text{CIFAR10/100}$, $\text{Caltech-256}$, $\text{ImageNet}$, $\text{Cityscapes}$, and $\text{BDD100K}$. Our results demonstrate that our adversarial approach learns an effective low dimensional latent space in large-scale settings and provides for a computationally efficient sampling method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00370](http://arxiv.org/abs/1904.00370)

##### PDF
[http://arxiv.org/pdf/1904.00370](http://arxiv.org/pdf/1904.00370)

