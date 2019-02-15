---
layout: post
title: "Categorical Metadata Representation for Customized Text Classification"
date: 2019-02-14 03:07:53
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention Sentiment_Classification Text_Classification Embedding Classification
author: Jihyeok Kim, Reinald Kim Amplayo, Kyungjae Lee, Sua Sung, Minji Seo, Seung-won Hwang
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of text classification has improved tremendously using intelligently engineered neural-based models, especially those injecting categorical metadata as additional information, e.g., using user/product information for sentiment classification. These information have been used to modify parts of the model (e.g., word embeddings, attention mechanisms) such that results can be customized according to the metadata. We observe that current representation methods for categorical metadata, which are devised for human consumption, are not as effective as claimed in popular classification methods, outperformed even by simple concatenation of categorical features in the final layer of the sentence encoder. We conjecture that categorical features are harder to represent for machine use, as available context only indirectly describes the category, and even such context is often scarce (for tail category). To this end, we propose to use basis vectors to effectively incorporate categorical metadata on various parts of a neural-based model. This additionally decreases the number of parameters dramatically, especially when the number of categorical features is large. Extensive experiments on various datasets with different properties are performed and show that through our method, we can represent categorical metadata more effectively to customize parts of the model, including unexplored ones, and increase the performance of the model greatly.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05196](http://arxiv.org/abs/1902.05196)

##### PDF
[http://arxiv.org/pdf/1902.05196](http://arxiv.org/pdf/1902.05196)

