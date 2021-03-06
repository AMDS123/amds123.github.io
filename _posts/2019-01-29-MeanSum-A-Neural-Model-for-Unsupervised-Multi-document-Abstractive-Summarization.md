---
layout: post
title: "MeanSum: A Neural Model for Unsupervised Multi-document Abstractive Summarization"
date: 2019-01-29 19:15:00
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Summarization
author: Eric Chu, Peter J. Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Abstractive summarization has been studied using neural sequence transduction methods with datasets of large, paired document-summary examples. However, such datasets are rare and the models trained from them do not generalize to other domains. Recently, some progress has been made in learning sequence-to-sequence mappings with only unpaired examples. In our work, we consider the setting where there are only documents (product or business reviews) with no summaries provided, and propose an end-to-end, neural model architecture to perform unsupervised abstractive summarization. Our proposed model consists of an auto-encoder where the mean of the representations of the input reviews decodes to a reasonable summary-review while not relying on any review-specific features. We consider variants of the proposed architecture and perform an ablation study to show the importance of specific components. We show through automated metrics and human evaluation that the generated summaries are highly abstractive, fluent, relevant, and representative of the average sentiment of the input reviews. Finally, we collect a reference evaluation dataset and show that our model outperforms a strong extractive baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.05739](http://arxiv.org/abs/1810.05739)

##### PDF
[http://arxiv.org/pdf/1810.05739](http://arxiv.org/pdf/1810.05739)

