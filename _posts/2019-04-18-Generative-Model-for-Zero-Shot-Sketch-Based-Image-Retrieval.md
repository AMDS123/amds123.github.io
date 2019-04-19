---
layout: post
title: "Generative Model for Zero-Shot Sketch-Based Image Retrieval"
date: 2019-04-18 00:11:04
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Vinay Kumar Verma, Aakansha Mishra, Ashish Mishra, Piyush Rai
mathjax: true
---

* content
{:toc}

##### Abstract
We present a probabilistic model for Sketch-Based Image Retrieval (SBIR) where, at retrieval time, we are given sketches from novel classes, that were not present at training time. Existing SBIR methods, most of which rely on learning class-wise correspondences between sketches and images, typically work well only for previously seen sketch classes, and result in poor retrieval performance on novel classes. To address this, we propose a generative model that learns to generate images, conditioned on a given novel class sketch. This enables us to reduce the SBIR problem to a standard image-to-image search problem. Our model is based on an inverse auto-regressive flow based variational autoencoder, with a feedback mechanism to ensure robust image generation. We evaluate our model on two very challenging datasets, Sketchy, and TU Berlin, with novel train-test split. The proposed approach significantly outperforms various baselines on both the datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08542](http://arxiv.org/abs/1904.08542)

##### PDF
[http://arxiv.org/pdf/1904.08542](http://arxiv.org/pdf/1904.08542)

