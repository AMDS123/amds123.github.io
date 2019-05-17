---
layout: post
title: "Effective Sentence Scoring Method using Bidirectional Language Model for Speech Recognition"
date: 2019-05-16 11:00:49
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Language_Model Recognition
author: Joongbo Shin, Yoonhyung Lee, Kyomin Jung
mathjax: true
---

* content
{:toc}

##### Abstract
In automatic speech recognition, many studies have shown performance improvements using language models (LMs). Recent studies have tried to use bidirectional LMs (biLMs) instead of conventional unidirectional LMs (uniLMs) for rescoring the $N$-best list decoded from the acoustic model. In spite of their theoretical benefits, the biLMs have not given notable improvements compared to the uniLMs in their experiments. This is because their biLMs do not consider the interaction between the two directions. In this paper, we propose a novel sentence scoring method considering the interaction between the past and the future words on the biLM. Our experimental results on the LibriSpeech corpus show that the biLM with the proposed sentence scoring outperforms the uniLM for the $N$-best list rescoring, consistently and significantly in all experimental conditions. The analysis of WERs by word position demonstrates that the biLM is more robust than the uniLM especially when a recognized sentence is short or a misrecognized word is at the beginning of the sentence.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06655](http://arxiv.org/abs/1905.06655)

##### PDF
[http://arxiv.org/pdf/1905.06655](http://arxiv.org/pdf/1905.06655)

