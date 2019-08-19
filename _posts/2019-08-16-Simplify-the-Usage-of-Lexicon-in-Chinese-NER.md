---
layout: post
title: "Simplify the Usage of Lexicon in Chinese NER"
date: 2019-08-16 13:35:24
categories: arXiv_CL
tags: arXiv_CL Inference RNN Recognition
author: Minlong Peng, Ruotian Ma, Qi Zhang, Xuanjing Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, many works have tried to utilizing word lexicon to augment the performance of Chinese named entity recognition (NER). As a representative work in this line, Lattice-LSTM \cite{zhang2018chinese} has achieved new state-of-the-art performance on several benchmark Chinese NER datasets. However, Lattice-LSTM suffers from a complicated model architecture, resulting in low computational efficiency. This will heavily limit its application in many industrial areas, which require real-time NER response. In this work, we ask the question: if we can simplify the usage of lexicon and, at the same time, achieve comparative performance with Lattice-LSTM for Chinese NER? Started with this question and motivated by the idea of Lattice-LSTM, we propose a concise but effective method to incorporate the lexicon information into the vector representations of characters. This way, our method can avoid introducing a complicated sequence modeling architecture to model the lexicon information. Instead, it only needs to subtly adjust the character representation layer of the neural sequence model. Experimental study on four benchmark Chinese NER datasets shows that our method can achieve much faster inference speed, comparative or better performance over Lattice-LSTM and its follwees. It also shows that our method can be easily transferred across difference neural architectures.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05969](https://arxiv.org/abs/1908.05969)

##### PDF
[https://arxiv.org/pdf/1908.05969](https://arxiv.org/pdf/1908.05969)

