---
layout: post
title: "Exploring Fine-Tuned Embeddings that Model Intensifiers for Emotion Analysis"
date: 2019-04-05 17:13:01
categories: arXiv_CL
tags: arXiv_CL Sentiment Embedding Classification Language_Model Prediction
author: Laura Bostan, Roman Klinger
mathjax: true
---

* content
{:toc}

##### Abstract
Adjective phrases like "a little bit surprised", "completely shocked", or "not stunned at all" are not handled properly by currently published state-of-the-art emotion classification and intensity prediction systems which use pre-dominantly non-contextualized word embeddings as input. Based on this finding, we analyze differences between embeddings used by these systems in regard to their capability of handling such cases. Furthermore, we argue that intensifiers in context of emotion words need special treatment, as is established for sentiment polarity classification, but not for more fine-grained emotion prediction. To resolve this issue, we analyze different aspects of a post-processing pipeline which enriches the word representations of such phrases. This includes expansion of semantic spaces at the phrase level and sub-word level followed by retrofitting to emotion lexica. We evaluate the impact of these steps with A La Carte and Bag-of-Substrings extensions based on pretrained GloVe, Word2vec, and fastText embeddings against a crowd-sourced corpus of intensity annotations for tweets containing our focus phrases. We show that the fastText-based models do not gain from handling these specific phrases under inspection. For Word2vec embeddings, we show that our post-processing pipeline improves the results by up to 8% on a novel dataset densely populated with intensifiers.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.03164](https://arxiv.org/abs/1904.03164)

##### PDF
[https://arxiv.org/pdf/1904.03164](https://arxiv.org/pdf/1904.03164)

