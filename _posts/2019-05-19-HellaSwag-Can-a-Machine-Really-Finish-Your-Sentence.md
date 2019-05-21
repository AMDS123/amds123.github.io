---
layout: post
title: "HellaSwag: Can a Machine Really Finish Your Sentence?"
date: 2019-05-19 23:57:23
categories: arXiv_CL
tags: arXiv_CL Adversarial Inference
author: Rowan Zellers, Ari Holtzman, Yonatan Bisk, Ali Farhadi, Yejin Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work by Zellers et al. (2018) introduced a new task of commonsense natural language inference: given an event description such as "A woman sits at a piano," a machine must select the most likely followup: "She sets her fingers on the keys." With the introduction of BERT, near human-level performance was reached. Does this mean that machines can perform human level commonsense inference? 
 In this paper, we show that commonsense inference still proves difficult for even state-of-the-art models, by presenting HellaSwag, a new challenge dataset. Though its questions are trivial for humans (&gt;95% accuracy), state-of-the-art models struggle (&lt;48%). We achieve this via Adversarial Filtering (AF), a data collection paradigm wherein a series of discriminators iteratively select an adversarial set of machine-generated wrong answers. AF proves to be surprisingly robust. The key insight is to scale up the length and complexity of the dataset examples towards a critical 'Goldilocks' zone wherein generated text is ridiculous to humans, yet often misclassified by state-of-the-art models. 
 Our construction of HellaSwag, and its resulting difficulty, sheds light on the inner workings of deep pretrained models. More broadly, it suggests a new path forward for NLP research, in which benchmarks co-evolve with the evolving state-of-the-art in an adversarial way, so as to present ever-harder challenges.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07830](http://arxiv.org/abs/1905.07830)

##### PDF
[http://arxiv.org/pdf/1905.07830](http://arxiv.org/pdf/1905.07830)

