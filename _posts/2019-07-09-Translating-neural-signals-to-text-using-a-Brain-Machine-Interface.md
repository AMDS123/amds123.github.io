---
layout: post
title: "Translating neural signals to text using a Brain-Machine Interface"
date: 2019-07-09 16:07:38
categories: arXiv_CL
tags: arXiv_CL Knowledge Face RNN
author: Janaki Sheth, Ariel Tankus, Michelle Tran, Nader Pouratian, Itzhak Fried, William Speier
mathjax: true
---

* content
{:toc}

##### Abstract
Brain-Computer Interfaces (BCI) help patients with faltering communication abilities due to neurodegenerative diseases produce text or speech output by direct neural processing. However, practical implementation of such a system has proven difficult due to limitations in speed, accuracy, and generalizability of the existing interfaces. To this end, we aim to create a BCI system that decodes text directly from neural signals. We implement a framework that initially isolates frequency bands in the input signal encapsulating differential information regarding production of various phonemic classes. These bands then form a feature set that feeds into an LSTM which discerns at each time point probability distributions across all phonemes uttered by a subject. Finally, these probabilities are fed into a particle filtering algorithm which incorporates prior knowledge of the English language to output text corresponding to the decoded word. Performance of this model on data obtained from six patients shows encouragingly high levels of accuracy at speeds and bit rates significantly higher than existing BCI communication systems. Further, in producing an output, our network abstains from constraining the reconstructed word to be from a given bag-of-words, unlike previous studies. The success of our proposed approach, offers promise for the employment of a BCI interface by patients in unfettered, naturalistic environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04265](http://arxiv.org/abs/1907.04265)

##### PDF
[http://arxiv.org/pdf/1907.04265](http://arxiv.org/pdf/1907.04265)

