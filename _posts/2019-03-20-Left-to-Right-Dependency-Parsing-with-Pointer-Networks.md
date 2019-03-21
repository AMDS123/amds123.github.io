---
layout: post
title: "Left-to-Right Dependency Parsing with Pointer Networks"
date: 2019-03-20 11:19:58
categories: arXiv_CL
tags: arXiv_CL
author: Daniel Fern&#xe1;ndez-Gonz&#xe1;lez, Carlos G&#xf3;mez-Rodr&#xed;guez
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel transition-based algorithm that straightforwardly parses sentences from left to right by building $n$ attachments, with $n$ being the length of the input sentence. Similarly to the recent stack-pointer parser by Ma et al. (2018), we use the pointer network framework that, given a word, can directly point to a position from the sentence. However, our left-to-right approach is simpler than the original top-down stack-pointer parser (not requiring a stack) and reduces transition sequence length in half, from 2$n$-1 actions to $n$. This results in a quadratic non-projective parser that runs twice as fast as the original while achieving the best accuracy to date on the English PTB dataset (96.04% UAS, 94.43% LAS) among fully-supervised single-model dependency parsers, and improves over the former top-down transition system in the majority of languages tested.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08445](http://arxiv.org/abs/1903.08445)

##### PDF
[http://arxiv.org/pdf/1903.08445](http://arxiv.org/pdf/1903.08445)

