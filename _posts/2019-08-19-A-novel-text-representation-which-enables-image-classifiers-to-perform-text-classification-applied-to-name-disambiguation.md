---
layout: post
title: "A novel text representation which enables image classifiers to perform text classification, applied to name disambiguation"
date: 2019-08-19 17:28:29
categories: arXiv_AI
tags: arXiv_AI Image_Caption Text_Classification Image_Classification Classification
author: Stephen M. Petrie, T&#x27;Mir D. Julius
mathjax: true
---

* content
{:toc}

##### Abstract
Patent data are often used to study the process of innovation and research, but patent databases lack unique identifiers for individual inventors, making it difficult to study innovation processes at the individual level. Here we introduce an algorithm that performs highly accurate disambiguation of inventors (named entities) in US patent data (F1: 99.09%, precision: 99.41%, recall: 98.76%). The algorithm involves a novel method for converting text-based record data into abstract image representations, in which text from a given pairwise comparison between two inventor name records is converted into a 2D RGB (stacked) image representation. We train an image classification neural network to discriminate between such pairwise comparison images, and then use the trained network to label each pair of records as either matched (same inventor) or non-matched (different inventors). The resulting disambiguation algorithm produces highly accurate results, out-performing other inventor name disambiguation studies on US patent data. Our new text-to-image representation method could potentially be used more broadly for other NLP comparison problems, as it allows image-based processing techniques (e.g. image classification networks) to be applied to text-based comparison problems (such as disambiguation of academic publications, or data linkage problems).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07846](http://arxiv.org/abs/1908.07846)

##### PDF
[http://arxiv.org/pdf/1908.07846](http://arxiv.org/pdf/1908.07846)

