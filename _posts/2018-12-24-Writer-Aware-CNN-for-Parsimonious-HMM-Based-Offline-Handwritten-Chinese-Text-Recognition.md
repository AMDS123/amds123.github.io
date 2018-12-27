---
layout: post
title: "Writer-Aware CNN for Parsimonious HMM-Based Offline Handwritten Chinese Text Recognition"
date: 2018-12-24 02:38:08
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Language_Model Relation Recognition
author: Zi-Rui Wang, Jun Du, Jia-Ming Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the hybrid convolutional neural network hidden Markov model (CNN-HMM) has been introduced for offline handwritten Chinese text recognition (HCTR) and has achieved state-of-the-art performance. In a CNN-HMM system, a handwritten text line is modeled by a series of cascading HMMs, each representing one character, and the posterior distributions of HMM states are calculated by CNN. However, modeling each of the large vocabulary of Chinese characters with a uniform and fixed number of hidden states requires high memory and computational costs and makes the tens of thousands of HMM state classes confusing. Another key issue of CNN-HMM for HCTR is the diversified writing style, which leads to model strain and a significant performance decline for specific writers. To address these issues, we propose a writer-aware CNN based on parsimonious HMM (WCNN-PHMM). Validated on the ICDAR 2013 competition of CASIA-HWDB database, the more compact WCNN-PHMM of a 7360-class vocabulary can achieve a relative character error rate (CER) reduction of 16.6% over the conventional CNN-HMM without considering language modeling. Moreover, the state-tying results of PHMM explicitly show the information sharing among similar characters and the confusion reduction of tied state classes. Finally, we visualize the learned writer codes and demonstrate the strong relationship with the writing styles of different writers. To the best of our knowledge, WCNN-PHMM yields the best results on the ICDAR 2013 competition set, demonstrating its power when enlarging the size of the character vocabulary.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09809](http://arxiv.org/abs/1812.09809)

##### PDF
[http://arxiv.org/pdf/1812.09809](http://arxiv.org/pdf/1812.09809)

