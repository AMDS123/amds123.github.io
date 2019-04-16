---
layout: post
title: "Rare Words: A Major Problem for Contextualized Embeddings And How to Fix it by Attentive Mimicking"
date: 2019-04-14 15:26:52
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Timo Schick, Hinrich Sch&#xfc;tze
mathjax: true
---

* content
{:toc}

##### Abstract
Pretraining deep neural network architectures with a language modeling objective has brought large improvements for many natural language processing tasks. Exemplified by BERT, a recently proposed such architecture, we demonstrate that despite being trained on huge amounts of data, deep language models still struggle to understand rare words. To fix this problem, we adapt Attentive Mimicking, a method that was designed to explicitly learn embeddings for rare words, to deep language models. In order to make this possible, we introduce one-token approximation, a method that allows us to use Attentive Mimicking even when the underlying language model uses subword-based tokenization, i.e., it does not assign embeddings to all words. To evaluate our method, we create a novel dataset that tests the ability of language models to capture semantic properties of words without any task-specific fine-tuning. Using this dataset, we show that adding our adapted version of Attentive Mimicking to BERT does indeed substantially improve its understanding of rare words.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06707](http://arxiv.org/abs/1904.06707)

##### PDF
[http://arxiv.org/pdf/1904.06707](http://arxiv.org/pdf/1904.06707)

