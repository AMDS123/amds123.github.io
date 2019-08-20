---
layout: post
title: "Encoder-Agnostic Adaptation for Conditional Language Generation"
date: 2019-08-19 17:22:58
categories: arXiv_CL
tags: arXiv_CL Attention Text_Generation Language_Model
author: Zachary M. Ziegler, Luke Melas-Kyriazi, Sebastian Gehrmann, Alexander M. Rush
mathjax: true
---

* content
{:toc}

##### Abstract
Large pretrained language models have changed the way researchers approach discriminative natural language understanding tasks, leading to the dominance of approaches that adapt a pretrained model for arbitrary downstream tasks. However it is an open-question how to use similar techniques for language generation. Early results in the encoder-agnostic setting have been mostly negative. In this work we explore methods for adapting a pretrained language model to arbitrary conditional input. We observe that pretrained transformer models are sensitive to large parameter changes during tuning. We therefore propose an adaptation that directly injects arbitrary conditioning into self attention, an approach we call pseudo self attention. Through experiments on four diverse conditional text generation tasks we show that this encoder-agnostic technique outperforms strong baselines, produces coherent generations, and is data efficient.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06938](http://arxiv.org/abs/1908.06938)

##### PDF
[http://arxiv.org/pdf/1908.06938](http://arxiv.org/pdf/1908.06938)

