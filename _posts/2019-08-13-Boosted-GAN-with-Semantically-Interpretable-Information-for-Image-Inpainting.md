---
layout: post
title: "Boosted GAN with Semantically Interpretable Information for Image Inpainting"
date: 2019-08-13 06:05:24
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation GAN
author: Ang Li, Jianzhong Qi, Rui Zhang, Ramamohanarao Kotagiri
mathjax: true
---

* content
{:toc}

##### Abstract
Image inpainting aims at restoring missing region of corrupted images, which has many applications such as image restoration and object removal. However, current GAN-based inpainting models fail to explicitly consider the semantic consistency between restored images and original images. Forexample, given a male image with image region of one eye missing, current models may restore it with a female eye. This is due to the ambiguity of GAN-based inpainting models: these models can generate many possible restorations given a missing region. To address this limitation, our key insight is that semantically interpretable information (such as attribute and segmentation information) of input images (with missing regions) can provide essential guidance for the inpainting process. Based on this insight, we propose a boosted GAN with semantically interpretable information for image inpainting that consists of an inpainting network and a discriminative network. The inpainting network utilizes two auxiliary pretrained networks to discover the attribute and segmentation information of input images and incorporates them into the inpainting process to provide explicit semantic-level guidance. The discriminative network adopts a multi-level design that can enforce regularizations not only on overall realness but also on attribute and segmentation consistency with the original images. Experimental results show that our proposed model can preserve consistency on both attribute and segmentation level, and significantly outperforms the state-of-the-art models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04503](http://arxiv.org/abs/1908.04503)

##### PDF
[http://arxiv.org/pdf/1908.04503](http://arxiv.org/pdf/1908.04503)

