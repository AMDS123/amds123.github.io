---
layout: post
title: "Learning Semantic Sentence Embeddings using Sequential Pair-wise Discriminator"
date: 2019-03-14 19:14:10
categories: arXiv_AI
tags: arXiv_AI Sentiment Embedding
author: Badri N. Patro, Vinod K. Kurmi, Sandeep Kumar, Vinay P. Namboodiri
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method for obtaining sentence-level embeddings. While the problem of securing word-level embeddings is very well studied, we propose a novel method for obtaining sentence-level embeddings. This is obtained by a simple method in the context of solving the paraphrase generation task. If we use a sequential encoder-decoder model for generating paraphrase, we would like the generated paraphrase to be semantically close to the original sentence. One way to ensure this is by adding constraints for true paraphrase embeddings to be close and unrelated paraphrase candidate sentence embeddings to be far. This is ensured by using a sequential pair-wise discriminator that shares weights with the encoder that is trained with a suitable loss function. Our loss function penalizes paraphrase sentence embedding distances from being too large. This loss is used in combination with a sequential encoder-decoder network. We also validated our method by evaluating the obtained embeddings for a sentiment analysis task. The proposed method results in semantic embeddings and outperforms the state-of-the-art on the paraphrase generation and sentiment analysis task on standard datasets. These results are also shown to be statistically significant.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.00807](http://arxiv.org/abs/1806.00807)

##### PDF
[http://arxiv.org/pdf/1806.00807](http://arxiv.org/pdf/1806.00807)

