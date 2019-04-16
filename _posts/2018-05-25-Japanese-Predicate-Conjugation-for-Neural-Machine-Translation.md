---
layout: post
title: "Japanese Predicate Conjugation for Neural Machine Translation"
date: 2018-05-25 08:56:43
categories: arXiv_CL
tags: arXiv_CL Face NMT
author: Michiki Kurosawa, Yukio Matsumura, Hayahide Yamagishi, Mamoru Komachi
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) has a drawback in that can generate only high-frequency words owing to the computational costs of the softmax function in the output layer. In Japanese-English NMT, Japanese predicate conjugation causes an increase in vocabulary size. For example, one verb can have as many as 19 surface varieties. In this research, we focus on predicate conjugation for compressing the vocabulary size in Japanese. The vocabulary list is filled with the various forms of verbs. We propose methods using predicate conjugation information without discarding linguistic information. The proposed methods can generate low-frequency words and deal with unknown words. Two methods were considered to introduce conjugation information: the first considers it as a token (conjugation token) and the second considers it as an embedded vector (conjugation feature). The results using these methods demonstrate that the vocabulary size can be compressed by approximately 86.1% (Tanaka corpus) and the NMT models can output the words not in the training data set. Furthermore, BLEU scores improved by 0.91 points in Japanese-to-English translation, and 0.32 points in English-to-Japanese translation with ASPEC.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.10047](https://arxiv.org/abs/1805.10047)

##### PDF
[https://arxiv.org/pdf/1805.10047](https://arxiv.org/pdf/1805.10047)

