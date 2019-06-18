---
layout: post
title: "Interconnected Question Generation with Coreference Alignment and Conversation Flow Modeling"
date: 2019-06-17 08:30:55
categories: arXiv_CL
tags: arXiv_CL
author: Yifan Gao, Piji Li, Irwin King, Michael R. Lyu
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of generating interconnected questions in question-answering style conversations. Compared with previous works which generate questions based on a single sentence (or paragraph), this setting is different in two major aspects: (1) Questions are highly conversational. Almost half of them refer back to conversation history using coreferences. (2) In a coherent conversation, questions have smooth transitions between turns. We propose an end-to-end neural model with coreference alignment and conversation flow modeling. The coreference alignment modeling explicitly aligns coreferent mentions in conversation history with corresponding pronominal references in generated questions, which makes generated questions interconnected to conversation history. The conversation flow modeling builds a coherent conversation by starting questioning on the first few sentences in a text passage and smoothly shifting the focus to later parts. Extensive experiments show that our system outperforms several baselines and can generate highly conversational questions. The code implementation is released at https://github.com/Evan-Gao/conversational-QG.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06893](http://arxiv.org/abs/1906.06893)

##### PDF
[http://arxiv.org/pdf/1906.06893](http://arxiv.org/pdf/1906.06893)

