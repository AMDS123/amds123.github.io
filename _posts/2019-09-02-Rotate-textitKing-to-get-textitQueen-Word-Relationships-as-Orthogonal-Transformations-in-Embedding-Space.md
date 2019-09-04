---
layout: post
title: "Rotate $textit{King}$ to get $textit{Queen}$: Word Relationships as Orthogonal Transformations in Embedding Space"
date: 2019-09-02 01:36:33
categories: arXiv_CL
tags: arXiv_CL Embedding Relation
author: Kawin Ethayarajh
mathjax: true
---

* content
{:toc}

##### Abstract
A notable property of word embeddings is that word relationships can exist as linear substructures in the embedding space. For example, $\textit{gender}$ corresponds to $\vec{\textit{woman}} - \vec{\textit{man}}$ and $\vec{\textit{queen}} - \vec{\textit{king}}$. This, in turn, allows word analogies to be solved arithmetically: $\vec{\textit{king}} - \vec{\textit{man}} + \vec{\textit{woman}} \approx \vec{\textit{queen}}$. This property is notable because it suggests that models trained on word embeddings can easily learn such relationships as geometric translations. However, there is no evidence that models $\textit{exclusively}$ represent relationships in this manner. We document an alternative way in which downstream models might learn these relationships: orthogonal and linear transformations. For example, given a translation vector for $\textit{gender}$, we can find an orthogonal matrix $R$, representing a rotation and reflection, such that $R(\vec{\textit{king}}) \approx \vec{\textit{queen}}$ and $R(\vec{\textit{man}}) \approx \vec{\textit{woman}}$. Analogical reasoning using orthogonal transformations is almost as accurate as using vector arithmetic; using linear transformations is more accurate than both. Our findings suggest that these transformations can be as good a representation of word relationships as translation vectors.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00504](http://arxiv.org/abs/1909.00504)

##### PDF
[http://arxiv.org/pdf/1909.00504](http://arxiv.org/pdf/1909.00504)

