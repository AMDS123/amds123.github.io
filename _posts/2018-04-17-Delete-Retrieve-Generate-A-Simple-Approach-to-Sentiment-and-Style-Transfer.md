---
layout: post
title: "Delete, Retrieve, Generate: A Simple Approach to Sentiment and Style Transfer"
date: 2018-04-17 18:59:51
categories: arXiv_CV
tags: arXiv_CV Image_Caption Sentiment Review Adversarial Style_Transfer Caption
author: Juncen Li, Robin Jia, He He, Percy Liang
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the task of text attribute transfer: transforming a sentence to alter a specific attribute (e.g., sentiment) while preserving its attribute-independent content (e.g., changing "screen is just the right size" to "screen is too small"). Our training data includes only sentences labeled with their attribute (e.g., positive or negative), but not pairs of sentences that differ only in their attributes, so we must learn to disentangle attributes from attribute-independent content in an unsupervised way. Previous work using adversarial methods has struggled to produce high-quality outputs. In this paper, we propose simpler methods motivated by the observation that text attributes are often marked by distinctive phrases (e.g., "too small"). Our strongest method extracts content words by deleting phrases associated with the sentence's original attribute value, retrieves new phrases associated with the target attribute, and uses a neural model to fluently combine these into a final output. On human evaluation, our best method generates grammatical and appropriate responses on 22% more inputs than the best previous system, averaged over three attribute transfer datasets: altering sentiment of reviews on Yelp, altering sentiment of reviews on Amazon, and altering image captions to be more romantic or humorous.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.06437](https://arxiv.org/abs/1804.06437)

##### PDF
[https://arxiv.org/pdf/1804.06437](https://arxiv.org/pdf/1804.06437)

