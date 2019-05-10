---
layout: post
title: "Speech Emotion Recognition Using Multi-hop Attention Mechanism"
date: 2019-05-09 13:34:00
categories: arXiv_SD
tags: arXiv_SD Knowledge Attention RNN Classification Relation Recognition
author: Seunghyun Yoon, Seokhyun Byun, Subhadeep Dey, Kyomin Jung
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we are interested in exploiting textual and acoustic data of an utterance for the speech emotion classification task. The baseline approach models the information from audio and text independently using two deep neural networks (DNNs). The outputs from both the DNNs are then fused for classification. As opposed to using knowledge from both the modalities separately, we propose a framework to exploit acoustic information in tandem with lexical data. The proposed framework uses two bi-directional long short-term memory (BLSTM) for obtaining hidden representations of the utterance. Furthermore, we propose an attention mechanism, referred to as the multi-hop, which is trained to automatically infer the correlation between the modalities. The multi-hop attention first computes the relevant segments of the textual data corresponding to the audio signal. The relevant textual data is then applied to attend parts of the audio signal. To evaluate the performance of the proposed system, experiments are performed in the IEMOCAP dataset. Experimental results show that the proposed technique outperforms the state-of-the-art system by 6.5% relative improvement in terms of weighted accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10788](http://arxiv.org/abs/1904.10788)

##### PDF
[http://arxiv.org/pdf/1904.10788](http://arxiv.org/pdf/1904.10788)

