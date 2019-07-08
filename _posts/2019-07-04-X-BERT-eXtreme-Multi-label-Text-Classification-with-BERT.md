---
layout: post
title: "X-BERT: eXtreme Multi-label Text Classification with BERT"
date: 2019-07-04 18:54:52
categories: arXiv_AI
tags: arXiv_AI Text_Classification Classification Deep_Learning Relation Recommendation
author: Wei-Cheng Chang, Hsiang-Fu Yu, Kai Zhong, Yiming Yang, Inderjit Dhillon
mathjax: true
---

* content
{:toc}

##### Abstract
Extreme multi-label text classification (XMC) aims to tag each input text with the most relevant labels from an extremely large label set, such as those that arise in product categorization and e-commerce recommendation. Recently, pretrained language representation models such as BERT achieve remarkable state-of-the-art performance across a wide range of NLP tasks including sentence classification among small label sets (typically fewer than thousands). Indeed, there are several challenges in applying BERT to the XMC problem. The main challenges are: (i) the difficulty of capturing dependencies and correlations among labels, whose features may come from heterogeneous sources, and (ii) the tractability to scale to the extreme label setting as the model size can be very large and scale linearly with the size of the output space. To overcome these challenges, we propose X-BERT, the first feasible attempt to finetune BERT models for a scalable solution to the XMC problem. Specifically, X-BERT leverages both the label and document text to build label representations, which induces semantic label clusters in order to better model label dependencies. At the heart of X-BERT is finetuning BERT models to capture the contextual relations between input text and the induced label clusters. Finally, an ensemble of the different BERT models trained on heterogeneous label clusters leads to our best final model. Empirically, on a Wiki dataset with around 0.5 million labels, X-BERT achieves new state-of-the-art results where the precision@1 reaches 67:80%, a substantial improvement over 32.58%/60.91% of deep learning baseline fastText and competing XMC approach Parabel, respectively. This amounts to a 11.31% relative improvement over Parabel, which is indeed significant since the recent approach SLICE only has 5.53% relative improvement.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02331](http://arxiv.org/abs/1905.02331)

##### PDF
[http://arxiv.org/pdf/1905.02331](http://arxiv.org/pdf/1905.02331)

