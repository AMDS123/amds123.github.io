---
layout: post
title: "Self-supervised audio representation learning for mobile devices"
date: 2019-05-24 13:57:40
categories: arXiv_SD
tags: arXiv_SD Embedding Represenation_Learning Inference Language_Model
author: Marco Tagliasacchi, Beat Gfeller, Félix de Chaumont Quitry, Dominik Roblek
mathjax: true
---

* content
{:toc}

##### Abstract
We explore self-supervised models that can be potentially deployed on mobile devices to learn general purpose audio representations. Specifically, we propose methods that exploit the temporal context in the spectrogram domain. One method estimates the temporal gap between two short audio segments extracted at random from the same audio clip. The other methods are inspired by Word2Vec, a popular technique used to learn word embeddings, and aim at reconstructing a temporal spectrogram slice from past and future slices or, alternatively, at reconstructing the context of surrounding slices from the current slice. We focus our evaluation on small encoder architectures, which can be potentially run on mobile devices during both inference (re-using a common learned representation across multiple downstream tasks) and training (capturing the true data distribution without compromising users' privacy when combined with federated learning). We evaluate the quality of the embeddings produced by the self-supervised learning models, and show that they can be re-used for a variety of downstream tasks, and for some tasks even approach the performance of fully supervised models of similar size.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11796](https://arxiv.org/abs/1905.11796)

##### PDF
[https://arxiv.org/pdf/1905.11796](https://arxiv.org/pdf/1905.11796)

