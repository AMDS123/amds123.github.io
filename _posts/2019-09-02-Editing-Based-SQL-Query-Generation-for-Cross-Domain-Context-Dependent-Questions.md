---
layout: post
title: "Editing-Based SQL Query Generation for Cross-Domain Context-Dependent Questions"
date: 2019-09-02 16:24:57
categories: arXiv_CL
tags: arXiv_CL
author: Rui Zhang, Tao Yu, He Yang Er, Sungrok Shim, Eric Xue, Xi Victoria Lin, Tianze Shi, Caiming Xiong, Richard Socher, Dragomir Radev
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on the cross-domain context-dependent text-to-SQL generation task. Based on the observation that adjacent natural language questions are often linguistically dependent and their corresponding SQL queries tend to overlap, we utilize the interaction history by editing the previous predicted query to improve the generation quality. Our editing mechanism views SQL as sequences and reuses generation results at the token level in a simple manner. It is flexible to change individual tokens and robust to error propagation. Furthermore, to deal with complex table structures in different domains, we employ an utterance-table encoder and a table-aware decoder to incorporate the context of the user utterance and the table schema. We evaluate our approach on the SParC dataset and demonstrate the benefit of editing compared with the state-of-the-art baselines which generate SQL from scratch. Our code is available at https://github.com/ryanzhumich/sparc_atis_pytorch.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00786](http://arxiv.org/abs/1909.00786)

##### PDF
[http://arxiv.org/pdf/1909.00786](http://arxiv.org/pdf/1909.00786)

