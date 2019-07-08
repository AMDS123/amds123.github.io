---
layout: post
title: "Explaining Predictions from Tree-based Boosting Ensembles"
date: 2019-07-04 20:43:12
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Ana Lucic, Hinda Haned, Maarten de Rijke
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding how "black-box" models arrive at their predictions has sparked significant interest from both within and outside the AI community. Our work focuses on doing this by generating local explanations about individual predictions for tree-based ensembles, specifically Gradient Boosting Decision Trees (GBDTs). Given a correctly predicted instance in the training set, we wish to generate a counterfactual explanation for this instance, that is, the minimal perturbation of this instance such that the prediction flips to the opposite class. Most existing methods for counterfactual explanations are (1) model-agnostic, so they do not take into account the structure of the original model, and/or (2) involve building a surrogate model on top of the original model, which is not guaranteed to represent the original model accurately. There exists a method specifically for random forests; we wish to extend this method for GBDTs. This involves accounting for (1) the sequential dependency between trees and (2) training on the negative gradients instead of the original labels.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02582](http://arxiv.org/abs/1907.02582)

##### PDF
[http://arxiv.org/pdf/1907.02582](http://arxiv.org/pdf/1907.02582)

