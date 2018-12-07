---
layout: post
title: "Deep Learning Approaches for Question Answering on Knowledge Bases: an evaluation of architectural design choices"
date: 2018-12-06 14:11:25
categories: arXiv_AI
tags: arXiv_AI Knowledge Attention Inference RNN Deep_Learning
author: Sherzod Hakimov, Soufian Jebbara, Philipp Cimiano
mathjax: true
---

* content
{:toc}

##### Abstract
The task of answering natural language questions over knowledge bases has received wide attention in recent years. Various deep learning architectures have been proposed for this task. However, architectural design choices are typically not systematically compared nor evaluated under the same conditions. In this paper, we contribute to a better understanding of the impact of architectural design choices by evaluating four different architectures under the same conditions. We address the task of answering simple questions, consisting in predicting the subject and predicate of a triple given a question. In order to provide a fair comparison of different architectures, we evaluate them under the same strategy for inferring the subject, and compare different architectures for inferring the predicate. The architecture for inferring the subject is based on a standard LSTM model trained to recognize the span of the subject in the question and on a linking component that links the subject span to an entity in the knowledge base. The architectures for predicate inference are based on i) a standard softmax classifier ranging over all predicates as output, iii) a model that predicts a low-dimensional encoding of the property given entity representation and question, iii) a model that learns to score a pair of subject and predicate given the question as well as iv) a model based on the well-known FastText model. The comparison of architectures shows that FastText provides better results than other architectures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02536](http://arxiv.org/abs/1812.02536)

##### PDF
[http://arxiv.org/pdf/1812.02536](http://arxiv.org/pdf/1812.02536)

