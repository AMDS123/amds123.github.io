---
layout: post
title: "Vector of Locally-Aggregated Word Embeddings : A novel document-level embedding"
date: 2019-02-23 21:35:54
categories: arXiv_CL
tags: arXiv_CL Image_Caption Review Text_Classification Embedding Classification
author: Radu Tudor Ionescu, Andrei M. Butnaru
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel representation for text documents based on aggregating word embedding vectors into document embeddings. Our approach is inspired by the Vector of Locally-Aggregated Descriptors used for image representation, and it works as follows. First, the word embeddings gathered from a collection of documents are clustered by k-means in order to learn a codebook of semnatically-related word embeddings. Each word embedding is then associated to its nearest cluster centroid (codeword). The Vector of Locally-Aggregated Word Embeddings (VLAWE) representation of a document is then computed by accumulating the differences between each codeword vector and each word vector (from the document) associated to the respective codeword. We plug the VLAWE representation, which is learned in an unsupervised manner, into a classifier and show that it is useful for a diverse set of text classification tasks. We compare our approach with a broad range of recent state-of-the-art methods, demonstrating the effectiveness of our approach. Furthermore, we obtain a considerable improvement on the Movie Review data set, reporting an accuracy of 93.3%, which represents an absolute gain of 10% over the state-of-the-art approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08850](http://arxiv.org/abs/1902.08850)

##### PDF
[http://arxiv.org/pdf/1902.08850](http://arxiv.org/pdf/1902.08850)

