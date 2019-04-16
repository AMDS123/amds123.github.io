---
layout: post
title: "Dual Long Short-Term Memory Networks for Sub-Character Representation Learning"
date: 2018-01-04 12:09:09
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Embedding Represenation_Learning RNN Memory_Networks
author: Han He, Lei Wu, Xiaokun Yang, Hua Yan, Zhimin Gao, Yi Feng, George Townsend
mathjax: true
---

* content
{:toc}

##### Abstract
Characters have commonly been regarded as the minimal processing unit in Natural Language Processing (NLP). But many non-latin languages have hieroglyphic writing systems, involving a big alphabet with thousands or millions of characters. Each character is composed of even smaller parts, which are often ignored by the previous work. In this paper, we propose a novel architecture employing two stacked Long Short-Term Memory Networks (LSTMs) to learn sub-character level representation and capture deeper level of semantic meanings. To build a concrete study and substantiate the efficiency of our neural architecture, we take Chinese Word Segmentation as a research case example. Among those languages, Chinese is a typical case, for which every character contains several components called radicals. Our networks employ a shared radical level embedding to solve both Simplified and Traditional Chinese Word Segmentation, without extra Traditional to Simplified Chinese conversion, in such a highly end-to-end way the word segmentation can be significantly simplified compared to the previous work. Radical level embeddings can also capture deeper semantic meaning below character level and improve the system performance of learning. By tying radical and character embeddings together, the parameter count is reduced whereas semantic knowledge is shared and transferred between two levels, boosting the performance largely. On 3 out of 4 Bakeoff 2005 datasets, our method surpassed state-of-the-art results by up to 0.4%. Our results are reproducible, source codes and corpora are available on GitHub.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.08841](https://arxiv.org/abs/1712.08841)

##### PDF
[https://arxiv.org/pdf/1712.08841](https://arxiv.org/pdf/1712.08841)

