---
layout: post
title: "Handling Divergent Reference Texts when Evaluating Table-to-Text Generation"
date: 2019-06-03 21:13:07
categories: arXiv_CL
tags: arXiv_CL Text_Generation Relation
author: Bhuwan Dhingra, Manaal Faruqui, Ankur Parikh, Ming-Wei Chang, Dipanjan Das, William W. Cohen
mathjax: true
---

* content
{:toc}

##### Abstract
Automatically constructed datasets for generating text from semi-structured data (tables), such as WikiBio, often contain reference texts that diverge from the information in the corresponding semi-structured data. We show that metrics which rely solely on the reference texts, such as BLEU and ROUGE, show poor correlation with human judgments when those references diverge. We propose a new metric, PARENT, which aligns n-grams from the reference and generated texts to the semi-structured data before computing their precision and recall. Through a large scale human evaluation study of table-to-text models for WikiBio, we show that PARENT correlates with human judgments better than existing text generation metrics. We also adapt and evaluate the information extraction based evaluation proposed by Wiseman et al (2017), and show that PARENT has comparable correlation to it, while being easier to use. We show that PARENT is also applicable when the reference texts are elicited from humans using the data from the WebNLG challenge.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01081](http://arxiv.org/abs/1906.01081)

##### PDF
[http://arxiv.org/pdf/1906.01081](http://arxiv.org/pdf/1906.01081)

