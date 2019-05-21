---
layout: post
title: "Human-like machine thinking: Language guided imagination"
date: 2019-05-18 09:23:00
categories: arXiv_AI
tags: arXiv_AI GAN RNN
author: Feng Qi, Wenchuan Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Human thinking requires the brain to understand the meaning of language expression and to properly organize the thoughts flow using the language. However, current natural language processing models are primarily limited in the word probability estimation. Here, we proposed a Language guided imagination (LGI) network to incrementally learn the meaning and usage of numerous words and syntaxes, aiming to form a human-like machine thinking process. LGI contains three subsystems: (1) vision system that contains an encoder to disentangle the input or imagined scenarios into abstract population representations, and an imagination decoder to reconstruct imagined scenario from higher level representations; (2) Language system, that contains a binarizer to transfer symbol texts into binary vectors, an IPS (mimicking the human IntraParietal Sulcus, implemented by an LSTM) to extract the quantity information from the input texts, and a textizer to convert binary vectors into text symbols; (3) a PFC (mimicking the human PreFrontal Cortex, implemented by an LSTM) to combine inputs of both language and vision representations, and predict text symbols and manipulated images accordingly. LGI has incrementally learned eight different syntaxes (or tasks), with which a machine thinking loop has been formed and validated by the proper interaction between language and vision system. The paper provides a new architecture to let the machine learn, understand and use language in a human-like way that could ultimately enable a machine to construct fictitious 'mental' scenario and possess intelligence.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07562](http://arxiv.org/abs/1905.07562)

##### PDF
[http://arxiv.org/pdf/1905.07562](http://arxiv.org/pdf/1905.07562)

