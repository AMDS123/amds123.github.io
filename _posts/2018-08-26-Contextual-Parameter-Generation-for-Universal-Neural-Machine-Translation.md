---
layout: post
title: "Contextual Parameter Generation for Universal Neural Machine Translation"
date: 2018-08-26 01:17:50
categories: arXiv_CL
tags: arXiv_CL Embedding NMT Relation
author: Emmanouil Antonios Platanios, Mrinmaya Sachan, Graham Neubig, Tom Mitchell
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a simple modification to existing neural machine translation (NMT) models that enables using a single universal model to translate between multiple languages while allowing for language specific parameterization, and that can also be used for domain adaptation. Our approach requires no changes to the model architecture of a standard NMT system, but instead introduces a new component, the contextual parameter generator (CPG), that generates the parameters of the system (e.g., weights in a neural network). This parameter generator accepts source and target language embeddings as input, and generates the parameters for the encoder and the decoder, respectively. The rest of the model remains unchanged and is shared across all languages. We show how this simple modification enables the system to use monolingual data for training and also perform zero-shot translation. We further show it is able to surpass state-of-the-art performance for both the IWSLT-15 and IWSLT-17 datasets and that the learned language embeddings are able to uncover interesting relationships between languages.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.08493](https://arxiv.org/abs/1808.08493)

##### PDF
[https://arxiv.org/pdf/1808.08493](https://arxiv.org/pdf/1808.08493)

