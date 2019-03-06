---
layout: post
title: "What to Expect of Classifiers? Reasoning about Logistic Regression with Missing Features"
date: 2019-03-05 01:16:10
categories: arXiv_AI
tags: arXiv_AI Classification Prediction
author: Pasha Khosravi, Yitao Liang, YooJung Choi, Guy Van den Broeck
mathjax: true
---

* content
{:toc}

##### Abstract
While discriminative classifiers often yield strong predictive performance, missing feature values at prediction time can still be a challenge. Classifiers may not behave as expected under certain ways of substituting the missing values, since they inherently make assumptions about the data distribution they were trained on. In this paper, we propose a novel framework that classifies examples with missing features by computing the expected prediction on a given feature distribution. We then use geometric programming to learn a naive Bayes distribution that embeds a given logistic regression classifier and can efficiently take its expected predictions. Empirical evaluations show that our model achieves the same performance as the logistic regression with all features observed, and outperforms standard imputation techniques when features go missing during prediction time. Furthermore, we demonstrate that our method can be used to generate 'sufficient explanations' of logistic regression classifications, by removing features that do not affect the classification.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.01620](https://arxiv.org/abs/1903.01620)

##### PDF
[https://arxiv.org/pdf/1903.01620](https://arxiv.org/pdf/1903.01620)

