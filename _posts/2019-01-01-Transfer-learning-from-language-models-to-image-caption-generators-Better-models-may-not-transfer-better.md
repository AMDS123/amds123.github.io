---
layout: post
title: "Transfer learning from language models to image caption generators: Better models may not transfer better"
date: 2019-01-01 20:23:40
categories: arXiv_CL
tags: arXiv_CL Image_Caption Caption Embedding CNN Transfer_Learning Language_Model
author: Marc Tanti, Albert Gatt, Kenneth P. Camilleri
mathjax: true
---

* content
{:toc}

##### Abstract
When designing a neural caption generator, a convolutional neural network can be used to extract image features. Is it possible to also use a neural language model to extract sentence prefix features? We answer this question by trying different ways to transfer the recurrent neural network and embedding layer from a neural language model to an image caption generator. We find that image caption generators with transferred parameters perform better than those trained from scratch, even when simply pre-training them on the text of the same captions dataset it will later be trained on. We also find that the best language models (in terms of perplexity) do not result in the best caption generators after transfer learning.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.01216](https://arxiv.org/abs/1901.01216)

##### PDF
[https://arxiv.org/pdf/1901.01216](https://arxiv.org/pdf/1901.01216)

