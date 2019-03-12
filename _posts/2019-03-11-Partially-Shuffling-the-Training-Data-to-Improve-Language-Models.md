---
layout: post
title: "Partially Shuffling the Training Data to Improve Language Models"
date: 2019-03-11 08:20:13
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Ofir Press
mathjax: true
---

* content
{:toc}

##### Abstract
Although SGD requires shuffling the training data between epochs, currently none of the word-level language modeling systems do this. Naively shuffling all sentences in the training data would not permit the model to learn inter-sentence dependencies. Here we present a method that partially shuffles the training data between epochs. This method makes each batch random, while keeping most sentence ordering intact. It achieves new state of the art results on word-level language modeling on both the Penn Treebank and WikiText-2 datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.04167](https://arxiv.org/abs/1903.04167)

##### PDF
[https://arxiv.org/pdf/1903.04167](https://arxiv.org/pdf/1903.04167)

