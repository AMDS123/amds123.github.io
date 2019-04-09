---
layout: post
title: "Joint Causal Inference from Multiple Contexts"
date: 2019-04-08 12:42:55
categories: arXiv_AI
tags: arXiv_AI Knowledge GAN Inference Relation
author: Joris M. Mooij, Sara Magliacane, Tom Claassen
mathjax: true
---

* content
{:toc}

##### Abstract
The gold standard for discovering causal relations is by means of experimentation. Over the last decades, alternative methods have been proposed that can infer causal relations between variables from certain statistical patterns in purely observational data. We introduce Joint Causal Inference (JCI), a novel approach to causal discovery from multiple data sets that elegantly unifies both approaches. JCI is a causal modeling approach rather than a specific algorithm, and it can be used in combination with any causal discovery algorithm that can take into account certain background knowledge. The main idea is to reduce causal discovery from multiple datasets originating from different contexts (e.g., different experimental conditions) to causal discovery from a single pooled dataset by adding auxiliary context variables and incorporating applicable background knowledge on the causal relationships involving the context variables. We propose different flavours of JCI that differ in the amount of background knowledge that is assumed. JCI can deal with several different types of interventions in a unified fashion, does not require knowledge on intervention targets or types in case of interventional data, and allows one to fully exploit all the information in the joint distribution on system and context variables. We explain how some well-known causal discovery algorithms can be seen as implementations of the JCI framework, but we also propose novel implementations that are simple adaptations of existing causal discovery methods for purely observational data to the JCI setting. We evaluate different implementations of the JCI approach on synthetic data and on flow cytometry protein expression data and conclude that JCI implementations can outperform state-of-the-art causal discovery algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1611.10351](http://arxiv.org/abs/1611.10351)

##### PDF
[http://arxiv.org/pdf/1611.10351](http://arxiv.org/pdf/1611.10351)

