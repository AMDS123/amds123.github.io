---
layout: post
title: "One-Shot Learning for Text-to-SQL Generation"
date: 2019-04-26 06:29:29
categories: arXiv_CL
tags: arXiv_CL GAN Deep_Learning
author: Dongjun Lee, Jaesik Yoon, Jongyun Song, Sanggil Lee, Sungroh Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
Most deep learning approaches for text-to-SQL generation are limited to the WikiSQL dataset, which only supports very simple queries. Recently, template-based and sequence-to-sequence approaches were proposed to support complex queries, which contain join queries, nested queries, and other types. However, Finegan-Dollak et al. (2018) demonstrated that both the approaches lack the ability to generate SQL of unseen templates. In this paper, we propose a template-based one-shot learning model for the text-to-SQL generation so that the model can generate SQL of an untrained template based on a single example. First, we classify the SQL template using the Matching Network that is augmented by our novel architecture Candidate Search Network. Then, we fill the variable slots in the predicted template using the Pointer Network. We show that our model outperforms state-of-the-art approaches for various text-to-SQL datasets in two aspects: 1) the SQL generation accuracy for the trained templates, and 2) the adaptability to the unseen SQL templates based on a single example without any additional training.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11499](https://arxiv.org/abs/1905.11499)

##### PDF
[https://arxiv.org/pdf/1905.11499](https://arxiv.org/pdf/1905.11499)

