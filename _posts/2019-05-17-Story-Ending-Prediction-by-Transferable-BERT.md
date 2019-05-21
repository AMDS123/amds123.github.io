---
layout: post
title: "Story Ending Prediction by Transferable BERT"
date: 2019-05-17 23:52:08
categories: arXiv_CL
tags: arXiv_CL Sentiment Knowledge Sentiment_Classification Inference Classification Language_Model Prediction
author: Zhongyang Li, Xiao Ding, Ting Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances, such as GPT and BERT, have shown success in incorporating a pre-trained transformer language model and fine-tuning operation to improve downstream NLP systems. However, this framework still has some fundamental problems in effectively incorporating supervised knowledge from other related tasks. In this study, we investigate a transferable BERT (TransBERT) training framework, which can transfer not only general language knowledge from large-scale unlabeled data but also specific kinds of knowledge from various semantically related supervised tasks, for a target task. Particularly, we propose utilizing three kinds of transfer tasks, including natural language inference, sentiment classification, and next action prediction, to further train BERT based on a pre-trained model. This enables the model to get a better initialization for the target task. We take story ending prediction as the target task to conduct experiments. The final result, an accuracy of 91.8%, dramatically outperforms previous state-of-the-art baseline methods. Several comparative experiments give some helpful suggestions on how to select transfer tasks. Error analysis shows what are the strength and weakness of BERT-based models for story ending prediction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07504](http://arxiv.org/abs/1905.07504)

##### PDF
[http://arxiv.org/pdf/1905.07504](http://arxiv.org/pdf/1905.07504)

