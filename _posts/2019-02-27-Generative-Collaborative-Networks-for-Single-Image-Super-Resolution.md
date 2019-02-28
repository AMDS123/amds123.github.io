---
layout: post
title: "Generative Collaborative Networks for Single Image Super-Resolution"
date: 2019-02-27 11:34:10
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Mohamed El Amine Seddik, Mohamed Tamaazousti, John Lin
mathjax: true
---

* content
{:toc}

##### Abstract
A common issue of deep neural networks-based methods for the problem of Single Image Super-Resolution (SISR), is the recovery of finer texture details when super-resolving at large upscaling factors. This issue is particularly related to the choice of the objective loss function. In particular, recent works proposed the use of a VGG loss which consists in minimizing the error between the generated high resolution images and ground-truth in the feature space of a Convolutional Neural Network (VGG19), pre-trained on the very "large" ImageNet dataset. When considering the problem of super-resolving images with a distribution "far" from the ImageNet images distribution (\textit{e.g.,} satellite images), their proposed \textit{fixed} VGG loss is no longer relevant. In this paper, we present a general framework named \textit{Generative Collaborative Networks} (GCN), where the idea consists in optimizing the \textit{generator} (the mapping of interest) in the feature space of a \textit{features extractor} network. The two networks (generator and extractor) are \textit{collaborative} in the sense that the latter "helps" the former, by constructing discriminative and relevant features (not necessarily \textit{fixed} and possibly learned \textit{mutually} with the generator). We evaluate the GCN framework in the context of SISR, and we show that it results in a method that is adapted to super-resolution domains that are "far" from the ImageNet domain.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10467](http://arxiv.org/abs/1902.10467)

##### PDF
[http://arxiv.org/pdf/1902.10467](http://arxiv.org/pdf/1902.10467)

