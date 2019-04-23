---
layout: post
title: "Understanding Stability of Medical Concept Embeddings: Analysis and Prediction"
date: 2019-04-21 07:07:48
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Language_Model Prediction Relation
author: Grace E. Lee, Aixin Sun
mathjax: true
---

* content
{:toc}

##### Abstract
In biomedical area, medical concepts linked to external knowledge bases (e.g., UMLS) are frequently used for accurate and effective representations. There are many studies to develop embeddings for medical concepts on biomedical corpus and evaluate overall quality of concept embeddings. However, quality of individual concept embeddings has not been carefully investigated. We analyze the quality of medical concept embeddings trained with word2vec in terms of embedding stability. From the analysis, we observe that some of concept embeddings are out of the effect of different hyperparameter values in word2vec and remain with poor stability. Moreover, when stability of concept embeddings is analyzed in terms of frequency, many low-frequency concepts achieve high stability as high-frequency concepts do. The findings suggest that there are other factors influencing the stability of medical concept embeddings. In this paper, we propose a new factor, the distribution of context words to predict stability of medical concept embeddings. By estimating the distribution of context words using normalized entropy, we show that the skewed distribution has a moderate correlation with the stability of concept embeddings. The result demonstrates that a medical concept whose a large portion of context words is taken up by a few words is able to obtain high stability, even though its frequency is low. The clear correlation between the proposed factor and stability of medical concept embeddings allows to predict the medical concepts with low-quality embeddings even prior to training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09552](http://arxiv.org/abs/1904.09552)

##### PDF
[http://arxiv.org/pdf/1904.09552](http://arxiv.org/pdf/1904.09552)

