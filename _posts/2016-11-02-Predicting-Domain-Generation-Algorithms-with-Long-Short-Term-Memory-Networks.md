---
layout: post
title: "Predicting Domain Generation Algorithms with Long Short-Term Memory Networks"
date: 2016-11-02 20:34:56
categories: arXiv_CV
tags: arXiv_CV GAN RNN Classification Detection Memory_Networks
author: Jonathan Woodbridge, Hyrum S. Anderson, Anjum Ahuja, Daniel Grant
mathjax: true
---

* content
{:toc}

##### Abstract
Various families of malware use domain generation algorithms (DGAs) to generate a large number of pseudo-random domain names to connect to a command and control (C&C) server. In order to block DGA C&C traffic, security organizations must first discover the algorithm by reverse engineering malware samples, then generating a list of domains for a given seed. The domains are then either preregistered or published in a DNS blacklist. This process is not only tedious, but can be readily circumvented by malware authors using a large number of seeds in algorithms with multivariate recurrence properties (e.g., banjori) or by using a dynamic list of seeds (e.g., bedep). Another technique to stop malware from using DGAs is to intercept DNS queries on a network and predict whether domains are DGA generated. Such a technique will alert network administrators to the presence of malware on their networks. In addition, if the predictor can also accurately predict the family of DGAs, then network administrators can also be alerted to the type of malware that is on their networks. This paper presents a DGA classifier that leverages long short-term memory (LSTM) networks to predict DGAs and their respective families without the need for a priori feature extraction. Results are significantly better than state-of-the-art techniques, providing 0.9993 area under the receiver operating characteristic curve for binary classification and a micro-averaged F1 score of 0.9906. In other terms, the LSTM technique can provide a 90% detection rate with a 1:10000 false positive (FP) rate---a twenty times FP improvement over comparable methods. Experiments in this paper are run on open datasets and code snippets are provided to reproduce the results.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1611.00791](https://arxiv.org/abs/1611.00791)

##### PDF
[https://arxiv.org/pdf/1611.00791](https://arxiv.org/pdf/1611.00791)

