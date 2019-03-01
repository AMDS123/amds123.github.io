---
layout: post
title: "Efficient Contextual Representation Learning Without Softmax Layer"
date: 2019-02-28 18:19:14
categories: arXiv_CL
tags: arXiv_CL Embedding Represenation_Learning Language_Model
author: Liunian Harold Li, Patrick H. Chen, Cho-Jui Hsieh, Kai-Wei Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Contextual representation models have achieved great success in improving various downstream tasks. However, these language-model-based encoders are difficult to train due to the large parameter sizes and high computational complexity. By carefully examining the training procedure, we find that the softmax layer (the output layer) causes significant inefficiency due to the large vocabulary size. Therefore, we redesign the learning objective and propose an efficient framework for training contextual representation models. Specifically, the proposed approach bypasses the softmax layer by performing language modeling with dimension reduction, and allows the models to leverage pre-trained word embeddings. Our framework reduces the time spent on the output layer to a negligible level, eliminates almost all the trainable parameters of the softmax layer and performs language modeling without truncating the vocabulary. When applied to ELMo, our method achieves a 4 times speedup and eliminates 80% trainable parameters while achieving competitive performance on downstream tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.11269](http://arxiv.org/abs/1902.11269)

##### PDF
[http://arxiv.org/pdf/1902.11269](http://arxiv.org/pdf/1902.11269)

