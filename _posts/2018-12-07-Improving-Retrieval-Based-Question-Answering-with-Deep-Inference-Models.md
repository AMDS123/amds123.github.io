---
layout: post
title: "Improving Retrieval-Based Question Answering with Deep Inference Models"
date: 2018-12-07 10:44:14
categories: arXiv_CL
tags: arXiv_CL Knowledge Inference Deep_Learning
author: George-Sebastian Pirtoaca, Traian Rebedea, Stefan Ruseti
mathjax: true
---

* content
{:toc}

##### Abstract
Question answering is one of the most important and difficult applications at the border of information retrieval and natural language processing, especially when we talk about complex science questions which require some form of inference to determine the correct answer. In this paper, we present a two-step method that combines information retrieval techniques optimized for question answering with deep learning models for natural language inference in order to tackle the multi-choice question answering in the science domain. For each question-answer pair, we use standard retrieval-based models to find relevant candidate contexts and decompose the main problem into two different sub-problems. First, assign correctness scores for each candidate answer based on the context using retrieval models from Lucene. Second, we use deep learning architectures to compute if a candidate answer can be inferred from some well-chosen context consisting of sentences retrieved from the knowledge base. In the end, all these solvers are combined using a simple neural network to predict the correct answer. This proposed two-step model outperforms the best retrieval-based solver by over 3% in absolute accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02971](http://arxiv.org/abs/1812.02971)

##### PDF
[http://arxiv.org/pdf/1812.02971](http://arxiv.org/pdf/1812.02971)

