---
layout: post
title: "Semantic Classification of Tabular Datasets via Character-Level Convolutional Neural Networks"
date: 2019-01-24 15:31:11
categories: arXiv_CL
tags: arXiv_CL CNN Transfer_Learning Inference Classification Prediction
author: Paul Azunre, Craig Corcoran, Numa Dhamani, Jeffrey Gleason, Garrett Honke, David Sullivan, Rebecca Ruppel, Sandeep Verma, Jonathon Morgan
mathjax: true
---

* content
{:toc}

##### Abstract
A character-level convolutional neural network (CNN) motivated by applications in "automated machine learning" (AutoML) is proposed to semantically classify columns in tabular data. Simulated data containing a set of base classes is first used to learn an initial set of weights. Hand-labeled data from the CKAN repository is then used in a transfer-learning paradigm to adapt the initial weights to a more sophisticated representation of the problem (e.g., including more classes). In doing so, realistic data imperfections are learned and the set of classes handled can be expanded from the base set with reduced labeled data and computing power requirements. Results show the effectiveness and flexibility of this approach in three diverse domains: semantic classification of tabular data, age prediction from social media posts, and email spam classification. In addition to providing further evidence of the effectiveness of transfer learning in natural language processing (NLP), our experiments suggest that analyzing the semantic structure of language at the character level without additional metadata---i.e., network structure, headers, etc.---can produce competitive accuracy for type classification, spam classification, and social media age prediction. We present our open-source toolkit SIMON, an acronym for Semantic Inference for the Modeling of ONtologies, which implements this approach in a user-friendly and scalable/parallelizable fashion.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08456](http://arxiv.org/abs/1901.08456)

##### PDF
[http://arxiv.org/pdf/1901.08456](http://arxiv.org/pdf/1901.08456)

