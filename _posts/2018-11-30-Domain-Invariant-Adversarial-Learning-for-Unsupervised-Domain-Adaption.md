---
layout: post
title: "Domain-Invariant Adversarial Learning for Unsupervised Domain Adaption"
date: 2018-11-30 12:02:45
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Yexun Zhang, Ya Zhang, Yanfeng Wang, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised domain adaption aims to learn a powerful classifier for the target domain given a labeled source data set and an unlabeled target data set. To alleviate the effect of `domain shift', the major challenge in domain adaptation, studies have attempted to align the distributions of the two domains. Recent research has suggested that generative adversarial network (GAN) has the capability of implicitly capturing data distribution. In this paper, we thus propose a simple but effective model for unsupervised domain adaption leveraging adversarial learning. The same encoder is shared between the source and target domains which is expected to extract domain-invariant representations with the help of an adversarial discriminator. With the labeled source data, we introduce the center loss to increase the discriminative power of feature learned. We further align the conditional distribution of the two domains to enforce the discrimination of the features in the target domain. Unlike previous studies where the source features are extracted with a fixed pre-trained encoder, our method jointly learns feature representations of two domains. Moreover, by sharing the encoder, the model does not need to know the source of images during testing and hence is more widely applicable. We evaluate the proposed method on several unsupervised domain adaption benchmarks and achieve superior or comparable performance to state-of-the-art results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12751](http://arxiv.org/abs/1811.12751)

##### PDF
[http://arxiv.org/pdf/1811.12751](http://arxiv.org/pdf/1811.12751)

