---
layout: post
title: "Identity-preserving Face Recovery from Stylized Portraits"
date: 2019-04-07 09:18:59
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Fatemeh Shiri, Xin Yu, Fatih Porikli, Richard Hartley, Piotr Koniusz
mathjax: true
---

* content
{:toc}

##### Abstract
Given an artistic portrait, recovering the latent photorealistic face that preserves the subject's identity is challenging because the facial details are often distorted or fully lost in artistic portraits. We develop an Identity-preserving Face Recovery from Portraits (IFRP) method that utilizes a Style Removal network (SRN) and a Discriminative Network (DN). Our SRN, composed of an autoencoder with residual block-embedded skip connections, is designed to transfer feature maps of stylized images to the feature maps of the corresponding photorealistic faces. Owing to the Spatial Transformer Network (STN), SRN automatically compensates for misalignments of stylized portraits to output aligned realistic face images. To ensure the identity preservation, we promote the recovered and ground truth faces to share similar visual features via a distance measure which compares features of recovered and ground truth faces extracted from a pre-trained FaceNet network. DN has multiple convolutional and fully-connected layers, and its role is to enforce recovered faces to be similar to authentic faces. Thus, we can recover high-quality photorealistic faces from unaligned portraits while preserving the identity of the face in an image. By conducting extensive evaluations on a large-scale synthesized dataset and a hand-drawn sketch dataset, we demonstrate that our method achieves superior face recovery and attains state-of-the-art results. In addition, our method can recover photorealistic faces from unseen stylized portraits, artistic paintings, and hand-drawn sketches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04241](http://arxiv.org/abs/1904.04241)

##### PDF
[http://arxiv.org/pdf/1904.04241](http://arxiv.org/pdf/1904.04241)

