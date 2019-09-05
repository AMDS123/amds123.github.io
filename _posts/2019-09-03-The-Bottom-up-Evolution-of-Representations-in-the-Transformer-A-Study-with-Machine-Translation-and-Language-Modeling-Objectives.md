---
layout: post
title: "The Bottom-up Evolution of Representations in the Transformer: A Study with Machine Translation and Language Modeling Objectives"
date: 2019-09-03 18:06:03
categories: arXiv_CL
tags: arXiv_CL Language_Model Prediction Relation
author: Elena Voita, Rico Sennrich, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
We seek to understand how the representations of individual tokens and the structure of the learned feature space evolve between layers in deep neural networks under different learning objectives. We focus on the Transformers for our analysis as they have been shown effective on various tasks, including machine translation (MT), standard left-to-right language models (LM) and masked language modeling (MLM). Previous work used black-box probing tasks to show that the representations learned by the Transformer differ significantly depending on the objective. In this work, we use canonical correlation analysis and mutual information estimators to study how information flows across Transformer layers and how this process depends on the choice of learning objective. For example, as you go from bottom to top layers, information about the past in left-to-right language models gets vanished and predictions about the future get formed. In contrast, for MLM, representations initially acquire information about the context around the token, partially forgetting the token identity and producing a more generalized token representation. The token identity then gets recreated at the top MLM layers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01380](http://arxiv.org/abs/1909.01380)

##### PDF
[http://arxiv.org/pdf/1909.01380](http://arxiv.org/pdf/1909.01380)

