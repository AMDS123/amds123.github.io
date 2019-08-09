---
layout: post
title: "Key Fact as Pivot: A Two-Stage Model for Low Resource Table-to-Text Generation"
date: 2019-08-08 13:41:31
categories: arXiv_CL
tags: arXiv_CL Face Text_Generation Prediction
author: Shuming Ma, Pengcheng Yang, Tianyu Liu, Peng Li, Jie Zhou, Xu Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Table-to-text generation aims to translate the structured data into the unstructured text. Most existing methods adopt the encoder-decoder framework to learn the transformation, which requires large-scale training samples. However, the lack of large parallel data is a major practical problem for many domains. In this work, we consider the scenario of low resource table-to-text generation, where only limited parallel data is available. We propose a novel model to separate the generation into two stages: key fact prediction and surface realization. It first predicts the key facts from the tables, and then generates the text with the key facts. The training of key fact prediction needs much fewer annotated data, while surface realization can be trained with pseudo parallel corpus. We evaluate our model on a biography generation dataset. Our model can achieve $27.34$ BLEU score with only $1,000$ parallel data, while the baseline model only obtain the performance of $9.71$ BLEU score.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.03067](http://arxiv.org/abs/1908.03067)

##### PDF
[http://arxiv.org/pdf/1908.03067](http://arxiv.org/pdf/1908.03067)

