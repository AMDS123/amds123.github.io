---
layout: post
title: "Error-Correcting Neural Sequence Prediction"
date: 2019-01-21 17:17:06
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model Prediction
author: James O&#x27; Neill, Danushka Bollegala
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a novel neural language modelling (NLM) method based on \textit{error-correcting output codes} (ECOC), abbreviated as ECOC-NLM. This latent variable based approach provides a principled way to choose a varying amount of latent output codes and avoids exact softmax normalization. Instead of minimizing measures between the predicted probability distribution and true distribution, we use error-correcting codes to represent both predictions and outputs. Secondly, we propose multiple ways to improve accuracy and convergence rates by maximizing the separability between codes that correspond to classes proportional to word embedding similarities. Lastly, we introduce a novel method called \textit{Latent Mixture Sampling}, a technique that is used to mitigate exposure bias and can be integrated into training latent-based neural language models. This involves mixing the latent codes (i.e variables) of past predictions and past targets in one of two ways: (1) according to a predefined sampling schedule or (2) a differentiable sampling procedure whereby the mixing probability is learned throughout training by replacing the greedy argmax operation with a smooth approximation. In evaluating Codeword Mixture Sampling for ECOC-NLM, we also baseline it against CWMS in a closely related Hierarhical Softmax-based NLM.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07002](http://arxiv.org/abs/1901.07002)

##### PDF
[http://arxiv.org/pdf/1901.07002](http://arxiv.org/pdf/1901.07002)

