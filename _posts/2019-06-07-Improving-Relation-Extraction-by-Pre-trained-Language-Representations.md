---
layout: post
title: "Improving Relation Extraction by Pre-trained Language Representations"
date: 2019-06-07 13:31:09
categories: arXiv_CL
tags: arXiv_CL Relation_Extraction Classification Relation
author: Christoph Alt, Marc H&#xfc;bner, Leonhard Hennig
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art relation extraction methods typically rely on a set of lexical, syntactic, and semantic features, explicitly computed in a pre-processing step. Training feature extraction models requires additional annotated language resources, which severely restricts the applicability and portability of relation extraction to novel languages. Similarly, pre-processing introduces an additional source of error. To address these limitations, we introduce TRE, a Transformer for Relation Extraction, extending the OpenAI Generative Pre-trained Transformer [Radford et al., 2018]. Unlike previous relation extraction models, TRE uses pre-trained deep language representations instead of explicit linguistic features to inform the relation classification and combines it with the self-attentive Transformer architecture to effectively model long-range dependencies between entity mentions. TRE allows us to learn implicit linguistic features solely from plain text corpora by unsupervised pre-training, before fine-tuning the learned language representations on the relation extraction task. TRE obtains a new state-of-the-art result on the TACRED and SemEval 2010 Task 8 datasets, achieving a test F1 of 67.4 and 87.1, respectively. Furthermore, we observe a significant increase in sample efficiency. With only 20% of the training examples, TRE matches the performance of our baselines and our model trained from scratch on 100% of the TACRED dataset. We open-source our trained models, experiments, and source code.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03088](http://arxiv.org/abs/1906.03088)

##### PDF
[http://arxiv.org/pdf/1906.03088](http://arxiv.org/pdf/1906.03088)

