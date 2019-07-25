---
layout: post
title: "Optimal Transport-based Alignment of Learned Character Representations for String Similarity"
date: 2019-07-23 22:41:22
categories: arXiv_CL
tags: arXiv_CL CNN Detection
author: Derek Tam, Nicholas Monath, Ari Kobren, Aaron Traylor, Rajarshi Das, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
String similarity models are vital for record linkage, entity resolution, and search. In this work, we present STANCE --a learned model for computing the similarity of two strings. Our approach encodes the characters of each string, aligns the encodings using Sinkhorn Iteration (alignment is posed as an instance of optimal transport) and scores the alignment with a convolutional neural network. We evaluate STANCE's ability to detect whether two strings can refer to the same entity--a task we term alias detection. We construct five new alias detection datasets (and make them publicly available). We show that STANCE or one of its variants outperforms both state-of-the-art and classic, parameter-free similarity models on four of the five datasets. We also demonstrate STANCE's ability to improve downstream tasks by applying it to an instance of cross-document coreference and show that it leads to a 2.8 point improvement in B^3 F1 over the previous state-of-the-art approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10165](http://arxiv.org/abs/1907.10165)

##### PDF
[http://arxiv.org/pdf/1907.10165](http://arxiv.org/pdf/1907.10165)

