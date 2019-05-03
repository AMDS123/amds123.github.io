---
layout: post
title: "KnowBias: A Novel AI Method to Detect Polarity in Online Content"
date: 2019-05-02 13:24:55
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding Classification Relation
author: Aditya Saligrama
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce KnowBias, a system for detecting the degree of political bias in textual content such as social media posts and news articles. In the space of scalable text classification, a common problem is domain mismatch, where easily accessible training data (i.e., tweets) does not correspond in format to the desired testing domain (i.e., longer form article content). While universal text encoders such as word or sentence embeddings could be leveraged to train target agnostic classifiers, such schemes result in poor performance on long-form articles. Our key insight is that long-form articles are a mix of neutral and political sentences, while tweets are concentrated with opinion. We propose a two-step classification system that first automatically filters out neutral sentences from the input text document at evaluation time, and then the resulting text is input into a polarity classifier. We evaluate our two-step approach using a variety of test suites, including a set of tweets and long-form articles where annotations were crowd-sourced to decrease label noise, measuring accuracy and Spearman-rho rank correlation. In practice, KnowBias achieves a high accuracy of 86% (rho = 0.65) on these tweets and 75% (rho = 0.69) on long-form articles.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00724](http://arxiv.org/abs/1905.00724)

##### PDF
[http://arxiv.org/pdf/1905.00724](http://arxiv.org/pdf/1905.00724)

