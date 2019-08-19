---
layout: post
title: "On the Robustness of Projection Neural Networks For Efficient Text Representation: An Empirical Study"
date: 2019-08-14 14:48:07
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding Classification Prediction
author: Chinnadhurai Sankar, Sujith Ravi, Zornitsa Kozareva
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, there has been strong interest in developing natural language applications that live on personal devices such as mobile phones, watches and IoT with the objective to preserve user privacy and have low memory. Advances in Locality-Sensitive Hashing (LSH)-based projection networks have demonstrated state-of-the-art performance without any embedding lookup tables and instead computing on-the-fly text representations. However, previous works have not investigated "What makes projection neural networks effective at capturing compact representations for text classification?" and "Are these projection models resistant to perturbations and misspellings in input text?". In this paper, we analyze and answer these questions through perturbation analyses and by running experiments on multiple dialog act prediction tasks. Our results show that the projections are resistant to perturbations and misspellings compared to widely-used recurrent architectures that use word embeddings. On ATIS intent prediction task, when evaluated with perturbed input data, we observe that the performance of recurrent models that use word embeddings drops significantly by more than 30% compared to just 5% with projection networks, showing that LSH-based projection representations are robust and consistently lead to high quality performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05763](https://arxiv.org/abs/1908.05763)

##### PDF
[https://arxiv.org/pdf/1908.05763](https://arxiv.org/pdf/1908.05763)

