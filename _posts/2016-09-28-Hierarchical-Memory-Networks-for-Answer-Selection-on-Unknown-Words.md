---
layout: post
title: "Hierarchical Memory Networks for Answer Selection on Unknown Words"
date: 2016-09-28 10:03:05
categories: arXiv_CV
tags: arXiv_CV Attention Prediction Memory_Networks
author: Jiaming Xu, Jing Shi, Yiqun Yao, Suncong Zheng, Bo Xu, Bo Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, end-to-end memory networks have shown promising results on Question Answering task, which encode the past facts into an explicit memory and perform reasoning ability by making multiple computational steps on the memory. However, memory networks conduct the reasoning on sentence-level memory to output coarse semantic vectors and do not further take any attention mechanism to focus on words, which may lead to the model lose some detail information, especially when the answers are rare or unknown words. In this paper, we propose a novel Hierarchical Memory Networks, dubbed HMN. First, we encode the past facts into sentence-level memory and word-level memory respectively. Then, (k)-max pooling is exploited following reasoning module on the sentence-level memory to sample the (k) most relevant sentences to a question and feed these sentences into attention mechanism on the word-level memory to focus the words in the selected sentences. Finally, the prediction is jointly learned over the outputs of the sentence-level reasoning module and the word-level attention mechanism. The experimental results demonstrate that our approach successfully conducts answer selection on unknown words and achieves a better performance than memory networks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1609.08843](https://arxiv.org/abs/1609.08843)

##### PDF
[https://arxiv.org/pdf/1609.08843](https://arxiv.org/pdf/1609.08843)

