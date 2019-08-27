---
layout: post
title: "Well-Read Students Learn Better: The Impact of Student Initialization on Knowledge Distillation"
date: 2019-08-23 18:02:05
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Knowledge Sentiment_Classification Classification Language_Model
author: Iulia Turc, Ming-Wei Chang, Kenton Lee, Kristina Toutanova
mathjax: true
---

* content
{:toc}

##### Abstract
Recent developments in NLP have been accompanied by large, expensive models. Knowledge distillation is the standard method to realize these gains in applications with limited resources: a compact student is trained to recover the outputs of a powerful teacher. While most prior work investigates student architectures and transfer techniques, we focus on an often-neglected aspect---student initialization. We argue that a random starting point hinders students from fully leveraging the teacher expertise, even in the presence of a large transfer set. We observe that applying language model pre-training to students unlocks their generalization potential, surprisingly even for very compact networks. We conduct experiments on 4 NLP tasks and 24 sizes of Transformer-based students; for sentiment classification on the Amazon Book Reviews dataset, pre-training boosts size reduction and TPU speed-up from 3.1x/1.25x to 31x/16x. Extensive ablation studies dissect the interaction between pre-training and distillation, revealing a compound effect even when they are applied on the same unlabeled dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08962](http://arxiv.org/abs/1908.08962)

##### PDF
[http://arxiv.org/pdf/1908.08962](http://arxiv.org/pdf/1908.08962)

