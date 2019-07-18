---
layout: post
title: "STRASS: A Light and Effective Method for Extractive Summarization Based on Sentence Embeddings"
date: 2019-07-16 16:14:09
categories: arXiv_CL
tags: arXiv_CL Summarization Embedding Inference
author: L&#xe9;o Bouscarrat, Antoine Bonnefoy, Thomas Peel, C&#xe9;cile Pereira
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces STRASS: Summarization by TRAnsformation Selection and Scoring. It is an extractive text summarization method which leverages the semantic information in existing sentence embedding spaces. Our method creates an extractive summary by selecting the sentences with the closest embeddings to the document embedding. The model learns a transformation of the document embedding to minimize the similarity between the extractive summary and the ground truth summary. As the transformation is only composed of a dense layer, the training can be done on CPU, therefore, inexpensive. Moreover, inference time is short and linear according to the number of sentences. As a second contribution, we introduce the French CASS dataset, composed of judgments from the French Court of cassation and their corresponding summaries. On this dataset, our results show that our method performs similarly to the state of the art extractive methods with effective training and inferring time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07323](http://arxiv.org/abs/1907.07323)

##### PDF
[http://arxiv.org/pdf/1907.07323](http://arxiv.org/pdf/1907.07323)

