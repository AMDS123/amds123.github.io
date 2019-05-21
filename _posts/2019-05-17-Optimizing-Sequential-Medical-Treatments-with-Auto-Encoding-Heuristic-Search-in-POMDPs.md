---
layout: post
title: "Optimizing Sequential Medical Treatments with Auto-Encoding Heuristic Search in POMDPs"
date: 2019-05-17 20:33:21
categories: arXiv_AI
tags: arXiv_AI Inference RNN
author: Luchen Li, Matthieu Komorowski, Aldo A. Faisal
mathjax: true
---

* content
{:toc}

##### Abstract
Health-related data is noisy and stochastic in implying the true physiological states of patients, limiting information contained in single-moment observations for sequential clinical decision making. We model patient-clinician interactions as partially observable Markov decision processes (POMDPs) and optimize sequential treatment based on belief states inferred from history sequence. To facilitate inference, we build a variational generative model and boost state representation with a recurrent neural network (RNN), incorporating an auxiliary loss from sequence auto-encoding. Meanwhile, we optimize a continuous policy of drug levels with an actor-critic method where policy gradients are obtained from a stablized off-policy estimate of advantage function, with the value of belief state backed up by parallel best-first suffix trees. We exploit our methodology in optimizing dosages of vasopressor and intravenous fluid for sepsis patients using a retrospective intensive care dataset and evaluate the learned policy with off-policy policy evaluation (OPPE). The results demonstrate that modelling as POMDPs yields better performance than MDPs, and that incorporating heuristic search improves sample efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07465](http://arxiv.org/abs/1905.07465)

##### PDF
[http://arxiv.org/pdf/1905.07465](http://arxiv.org/pdf/1905.07465)

