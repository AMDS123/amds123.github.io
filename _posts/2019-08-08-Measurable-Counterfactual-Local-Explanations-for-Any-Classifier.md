---
layout: post
title: "Measurable Counterfactual Local Explanations for Any Classifier"
date: 2019-08-08 11:16:22
categories: arXiv_AI
tags: arXiv_AI Knowledge Classification Prediction
author: Adam White, Artur d&#x27;Avila Garcez
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for explaining the predictions of any classifier. In our approach, local explanations are expected to explain both the outcome of a prediction and how that prediction would change if 'things had been different'. Furthermore, we argue that satisfactory explanations cannot be dissociated from a notion and measure of fidelity, as advocated in the early days of neural networks' knowledge extraction. We introduce a definition of fidelity to the underlying classifier for local explanation models which is based on distances to a target decision boundary. A system called CLEAR: Counterfactual Local Explanations via Regression, is introduced and evaluated. CLEAR generates w-counterfactual explanations that state minimum changes necessary to flip a prediction's classification. CLEAR then builds local regression models, using the w-counterfactuals to measure and improve the fidelity of its regressions. By contrast, the popular LIME method, which also uses regression to generate local explanations, neither measures its own fidelity nor generates counterfactuals. CLEAR's regressions are found to have significantly higher fidelity than LIME's, averaging over 45% higher in this paper's four case studies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.03020](http://arxiv.org/abs/1908.03020)

##### PDF
[http://arxiv.org/pdf/1908.03020](http://arxiv.org/pdf/1908.03020)

