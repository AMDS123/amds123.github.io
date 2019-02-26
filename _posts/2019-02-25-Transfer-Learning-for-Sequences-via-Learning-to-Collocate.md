---
layout: post
title: "Transfer Learning for Sequences via Learning to Collocate"
date: 2019-02-25 05:04:11
categories: arXiv_AI
tags: arXiv_AI Sentiment Transfer_Learning RNN Classification
author: Wanyun Cui, Guangyu Zheng, Zhiqiang Shen, Sihang Jiang, Wei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Transfer learning aims to solve the data sparsity for a target domain by applying information of the source domain. Given a sequence (e.g. a natural language sentence), the transfer learning, usually enabled by recurrent neural network (RNN), represents the sequential information transfer. RNN uses a chain of repeating cells to model the sequence data. However, previous studies of neural network based transfer learning simply represents the whole sentence by a single vector, which is unfeasible for seq2seq and sequence labeling. Meanwhile, such layer-wise transfer learning mechanisms lose the fine-grained cell-level information from the source domain. 
 In this paper, we proposed the aligned recurrent transfer, ART, to achieve cell-level information transfer. ART is under the pre-training framework. Each cell attentively accepts transferred information from a set of positions in the source domain. Therefore, ART learns the cross-domain word collocations in a more flexible way. We conducted extensive experiments on both sequence labeling tasks (POS tagging, NER) and sentence classification (sentiment analysis). ART outperforms the state-of-the-arts over all experiments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09092](http://arxiv.org/abs/1902.09092)

##### PDF
[http://arxiv.org/pdf/1902.09092](http://arxiv.org/pdf/1902.09092)

