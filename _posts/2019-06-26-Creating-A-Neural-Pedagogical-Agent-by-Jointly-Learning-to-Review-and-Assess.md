---
layout: post
title: "Creating A Neural Pedagogical Agent by Jointly Learning to Review and Assess"
date: 2019-06-26 08:37:44
categories: arXiv_CL
tags: arXiv_CL Review Attention RNN Recommendation
author: Youngnam Lee, Youngduck Choi, Junghyun Cho, Alexander R. Fabbri, Hyunbin Loh, Chanyou Hwang, Yongku Lee, Sang-Wook Kim, Dragomir Radev
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning plays an increasing role in intelligent tutoring systems as both the amount of data available and specialization among students grow. Nowadays, these systems are frequently deployed on mobile applications. Users on such mobile education platforms are dynamic, frequently being added, accessing the application with varying levels of focus, and changing while using the service. The education material itself, on the other hand, is often static and is an exhaustible resource whose use in tasks such as problem recommendation must be optimized. The ability to update user models with respect to educational material in real-time is thus essential; however, existing approaches require time-consuming re-training of user features whenever new data is added. In this paper, we introduce a neural pedagogical agent for real-time user modeling in the task of predicting user response correctness, a central task for mobile education applications. Our model, inspired by work in natural language processing on sequence modeling and machine translation, updates user features in real-time via bidirectional recurrent neural networks with an attention mechanism over embedded question-response pairs. We experiment on the mobile education application SantaTOEIC, which has 559k users, 66M response data points as well as a set of 10k study problems each expert-annotated with topic tags and gathered since 2016. Our model outperforms existing approaches over several metrics in predicting user response correctness, notably out-performing other methods on new users without large question-response histories. Additionally, our attention mechanism and annotated tag set allow us to create an interpretable education platform, with a smart review system that addresses the aforementioned issue of varied user attention and problem exhaustion.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10910](http://arxiv.org/abs/1906.10910)

##### PDF
[http://arxiv.org/pdf/1906.10910](http://arxiv.org/pdf/1906.10910)

