---
layout: post
title: "Improving Transparency of Deep Neural Inference Process"
date: 2019-03-13 14:11:44
categories: arXiv_AI
tags: arXiv_AI Inference RNN Deep_Learning Quantitative
author: Hiroshi Kuwajima, Masayuki Tanaka, Masatoshi Okutomi
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning techniques are rapidly advanced recently, and becoming a necessity component for widespread systems. However, the inference process of deep learning is black-box, and not very suitable to safety-critical systems which must exhibit high transparency. In this paper, to address this black-box limitation, we develop a simple analysis method which consists of 1) structural feature analysis: lists of the features contributing to inference process, 2) linguistic feature analysis: lists of the natural language labels describing the visual attributes for each feature contributing to inference process, and 3) consistency analysis: measuring consistency among input data, inference (label), and the result of our structural and linguistic feature analysis. Our analysis is simplified to reflect the actual inference process for high transparency, whereas it does not include any additional black-box mechanisms such as LSTM for highly human readable results. We conduct experiments and discuss the results of our analysis qualitatively and quantitatively, and come to believe that our work improves the transparency of neural networks. Evaluated through 12,800 human tasks, 75% workers answer that input data and result of our feature analysis are consistent, and 70% workers answer that inference (label) and result of our feature analysis are consistent. In addition to the evaluation of the proposed analysis, we find that our analysis also provide suggestions, or possible next actions such as expanding neural network complexity or collecting training data to improve a neural network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05501](http://arxiv.org/abs/1903.05501)

##### PDF
[http://arxiv.org/pdf/1903.05501](http://arxiv.org/pdf/1903.05501)

