---
layout: post
title: "Constructing large scale biomedical knowledge bases from scratch with rapid annotation of interpretable patterns"
date: 2019-07-02 14:53:30
categories: arXiv_CL
tags: arXiv_CL Salient Knowledge Relation_Extraction Relation
author: Julien Fauqueur, Ashok Thillaisundara, Theodosia Togia
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge base construction is crucial for summarising, understanding and inferring relationships between biomedical entities. However, for many practical applications such as drug discovery, the scarcity of relevant facts (e.g. gene X is therapeutic target for disease Y) severely limits a domain expert's ability to create a usable knowledge base, either directly or by training a relation extraction model. 
 In this paper, we present a simple and effective method of extracting new facts with a pre-specified binary relationship type from the biomedical literature, without requiring any training data or hand-crafted rules. Our system discovers, ranks and presents the most salient patterns to domain experts in an interpretable form. By marking patterns as compatible with the desired relationship type, experts indirectly batch-annotate candidate pairs whose relationship is expressed with such patterns in the literature. Even with a complete absence of seed data, experts are able to discover thousands of high-quality pairs with the desired relationship within minutes. When a small number of relevant pairs do exist - even when their relationship is more general (e.g. gene X is biologically associated with disease Y) than the relationship of interest - our system leverages them in order to i) learn a better ranking of the patterns to be annotated or ii) generate weakly labelled pairs in a fully automated manner. 
 We evaluate our method both intrinsically and via a downstream knowledge base completion task, and show that it is an effective way of constructing knowledge bases when few or no relevant facts are already available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01417](http://arxiv.org/abs/1907.01417)

##### PDF
[http://arxiv.org/pdf/1907.01417](http://arxiv.org/pdf/1907.01417)

