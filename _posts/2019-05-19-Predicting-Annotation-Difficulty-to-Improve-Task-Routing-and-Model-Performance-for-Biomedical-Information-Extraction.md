---
layout: post
title: "Predicting Annotation Difficulty to Improve Task Routing and Model Performance for Biomedical Information Extraction"
date: 2019-05-19 18:28:34
categories: arXiv_CL
tags: arXiv_CL Prediction
author: Yinfei Yang, Oshin Agarwal, Chris Tar, Byron C. Wallace, Ani Nenkova
mathjax: true
---

* content
{:toc}

##### Abstract
Modern NLP systems require high-quality annotated data. In specialized domains, expert annotations may be prohibitively expensive. An alternative is to rely on crowdsourcing to reduce costs at the risk of introducing noise. In this paper we demonstrate that directly modeling instance difficulty can be used to improve model performance, and to route instances to appropriate annotators. Our difficulty prediction model combines two learned representations: a `universal' encoder trained on out-of-domain data, and a task-specific encoder. Experiments on a complex biomedical information extraction task using expert and lay annotators show that: (i) simply excluding from the training data instances predicted to be difficult yields a small boost in performance; (ii) using difficulty scores to weight instances during training provides further, consistent gains; (iii) assigning instances predicted to be difficult to domain experts is an effective strategy for task routing. Our experiments confirm the expectation that for specialized tasks expert annotations are higher quality than crowd labels, and hence preferable to obtain if practical. Moreover, augmenting small amounts of expert data with a larger set of lay annotations leads to further improvements in model performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07791](http://arxiv.org/abs/1905.07791)

##### PDF
[http://arxiv.org/pdf/1905.07791](http://arxiv.org/pdf/1905.07791)

