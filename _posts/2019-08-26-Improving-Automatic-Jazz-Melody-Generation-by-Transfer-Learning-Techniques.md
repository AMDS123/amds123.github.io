---
layout: post
title: "Improving Automatic Jazz Melody Generation by Transfer Learning Techniques"
date: 2019-08-26 05:57:21
categories: arXiv_AI
tags: arXiv_AI Transfer_Learning
author: Hsiao-Tzu Hung, Chung-Yang Wang, Yi-Hsuan Yang, Hsin-Min Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we tackle the problem of transfer learning for Jazz automatic generation. Jazz is one of representative types of music, but the lack of Jazz data in the MIDI format hinders the construction of a generative model for Jazz. Transfer learning is an approach aiming to solve the problem of data insufficiency, so as to transfer the common feature from one domain to another. In view of its success in other machine learning problems, we investigate whether, and how much, it can help improve automatic music generation for under-resourced musical genres. Specifically, we use a recurrent variational autoencoder as the generative model, and use a genre-unspecified dataset as the source dataset and a Jazz-only dataset as the target dataset. Two transfer learning methods are evaluated using six levels of source-to-target data ratios. The first method is to train the model on the source dataset, and then fine-tune the resulting model parameters on the target dataset. The second method is to train the model on both the source and target datasets at the same time, but add genre labels to the latent vectors and use a genre classifier to improve Jazz generation. The evaluation results show that the second method seems to perform better overall, but it cannot take full advantage of the genre-unspecified dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09484](http://arxiv.org/abs/1908.09484)

##### PDF
[http://arxiv.org/pdf/1908.09484](http://arxiv.org/pdf/1908.09484)

