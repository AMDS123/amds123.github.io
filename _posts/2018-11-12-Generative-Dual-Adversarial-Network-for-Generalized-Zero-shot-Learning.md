---
layout: post
title: "Generative Dual Adversarial Network for Generalized Zero-shot Learning"
date: 2018-11-12 17:04:51
categories: arXiv_CV
tags: arXiv_CV Adversarial Embedding Classification
author: He Huang, Changhu Wang, Philip S. Yu, Chang-Dong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the problem of generalized zero-shot learning which requires the model to train on image-label pairs from some seen classes and test on the task of classifying new images from both seen and unseen classes. Most previous models try to learn a fixed one-directional mapping between visual and semantic space, while some recently proposed generative methods try to generate image features for unseen classes so that the zero-shot learning problem becomes a traditional fully-supervised classification problem. In this paper, we propose a novel model that provides a unified framework for three different approaches: visual-&gt; semantic mapping, semantic-&gt;visual mapping, and metric learning. Specifically, our proposed model consists of a feature generator that can generate various visual features given class embeddings as input, a regressor that maps each visual feature back to its corresponding class embedding, and a discriminator that learns to evaluate the closeness of an image feature and a class embedding. All three components are trained under the combination of cyclic consistency loss and dual adversarial loss. Experimental results show that our model not only preserves higher accuracy in classifying images from seen classes, but also performs better than existing state-of-the-art models in in classifying images from unseen classes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04857](http://arxiv.org/abs/1811.04857)

##### PDF
[http://arxiv.org/pdf/1811.04857](http://arxiv.org/pdf/1811.04857)

