---
layout: post
title: "What's in a Name? Reducing Bias in Bios without Access to Protected Attributes"
date: 2019-04-10 15:10:37
categories: arXiv_CL
tags: arXiv_CL Embedding Classification Relation
author: Alexey Romanov, Maria De-Arteaga, Hanna Wallach, Jennifer Chayes, Christian Borgs, Alexandra Chouldechova, Sahin Geyik, Krishnaram Kenthapadi, Anna Rumshisky, Adam Tauman Kalai
mathjax: true
---

* content
{:toc}

##### Abstract
There is a growing body of work that proposes methods for mitigating bias in machine learning systems. These methods typically rely on access to protected attributes such as race, gender, or age. However, this raises two significant challenges: (1) protected attributes may not be available or it may not be legal to use them, and (2) it is often desirable to simultaneously consider multiple protected attributes, as well as their intersections. In the context of mitigating bias in occupation classification, we propose a method for discouraging correlation between the predicted probability of an individual's true occupation and a word embedding of their name. This method leverages the societal biases that are encoded in word embeddings, eliminating the need for access to protected attributes. Crucially, it only requires access to individuals' names at training time and not at deployment time. We evaluate two variations of our proposed method using a large-scale dataset of online biographies. We find that both variations simultaneously reduce race and gender biases, with almost no reduction in the classifier's overall true positive rate.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05233](http://arxiv.org/abs/1904.05233)

##### PDF
[http://arxiv.org/pdf/1904.05233](http://arxiv.org/pdf/1904.05233)

