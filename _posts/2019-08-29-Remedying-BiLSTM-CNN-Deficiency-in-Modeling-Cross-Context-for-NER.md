---
layout: post
title: "Remedying BiLSTM-CNN Deficiency in Modeling Cross-Context for NER"
date: 2019-08-29 04:36:30
categories: arXiv_CL
tags: arXiv_CL Attention RNN
author: Peng-Hsuan Li, Tsu-Jui Fu, Wei-Yun Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Recent researches prevalently used BiLSTM-CNN as a core module for NER in a sequence-labeling setup. This paper formally shows the limitation of BiLSTM-CNN encoders in modeling cross-context patterns for each word, i.e., patterns crossing past and future for a specific time step. Two types of cross-structures are used to remedy the problem: A BiLSTM variant with cross-link between layers; a multi-head self-attention mechanism. These cross-structures bring consistent improvements across a wide range of NER domains for a core system using BiLSTM-CNN without additional gazetteers, POS taggers, language-modeling, or multi-task supervision. The model surpasses comparable previous models on OntoNotes 5.0 and WNUT 2017 by 1.4% and 4.6%, especially improving emerging, complex, confusing, and multi-token entity mentions, showing the importance of remedying the core module of NER.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11046](http://arxiv.org/abs/1908.11046)

##### PDF
[http://arxiv.org/pdf/1908.11046](http://arxiv.org/pdf/1908.11046)

