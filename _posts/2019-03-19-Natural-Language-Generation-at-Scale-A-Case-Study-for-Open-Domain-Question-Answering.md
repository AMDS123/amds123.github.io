---
layout: post
title: "Natural Language Generation at Scale: A Case Study for Open Domain Question Answering"
date: 2019-03-19 16:35:29
categories: arXiv_CL
tags: arXiv_CL Knowledge_Graph Knowledge QA Embedding
author: Alessandra Cervone, Chandra Khatri, Rahul Goel, Behnam Hedayatnia, Anu Venkatesh, Dilek Hakkani-Tur, Raefer Gabriel
mathjax: true
---

* content
{:toc}

##### Abstract
Current approaches to Natural Language Generation (NLG) focus on domain-specific, task-oriented dialogs (e.g. restaurant booking) using limited ontologies (up to 20 slot types), usually without considering the previous conversation context. Furthermore, these approaches require large amounts of data for each domain, and do not benefit from examples that may be available for other domains. This work explores the feasibility of statistical NLG for conversational applications with larger ontologies, which may be required by multi-domain dialog systems as well as open-domain knowledge graph based question answering (QA). We focus on modeling NLG through an Encoder-Decoder framework using a large dataset of interactions between real-world users and a conversational agent for open-domain QA. First, we investigate the impact of increasing the number of slot types on the generation quality and experiment with different partitions of the QA data with progressively larger ontologies (up to 369 slot types). Second, we explore multi-task learning for NLG and benchmark our model on a popular NLG dataset and perform experiments with open-domain QA and task-oriented dialog. Finally, we integrate conversation context by using context embeddings as an additional input for generation to improve response quality. Our experiments show the feasibility of learning statistical NLG models for open-domain contextual QA with larger ontologies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08097](http://arxiv.org/abs/1903.08097)

##### PDF
[http://arxiv.org/pdf/1903.08097](http://arxiv.org/pdf/1903.08097)

