---
layout: post
title: "FairMod - Making Predictive Models Discrimination Aware"
date: 2018-11-05 02:07:03
categories: arXiv_AI
tags: arXiv_AI Optimization Classification Prediction
author: Jixue Liu, Jiuyong Li, Lin Liu, Thuc Duy Le, Feiyue Ye, Gefei Li
mathjax: true
---

* content
{:toc}

##### Abstract
Predictive models such as decision trees and neural networks may produce discrimination in their predictions. This paper proposes a method to post-process the predictions of a predictive model to make the processed predictions non-discriminatory. The method considers multiple protected variables together. Multiple protected variables make the problem more challenging than a simple protected variable. The method uses a well-cited discrimination metric and adapts it to allow the specification of explanatory variables, such as position, profession, education, that describe the contexts of the applications. It models the post-processing of predictions problem as a nonlinear optimization problem to find best adjustments to the predictions so that the discrimination constraints of all protected variables are all met at the same time. The proposed method is independent of classification methods. It can handle the cases that existing methods cannot handle: satisfying multiple protected attributes at the same time, allowing multiple explanatory attributes, and being independent of classification model types. An evaluation using four real world data sets shows that the proposed method is as effectively as existing methods, in addition to its extra power.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01480](http://arxiv.org/abs/1811.01480)

##### PDF
[http://arxiv.org/pdf/1811.01480](http://arxiv.org/pdf/1811.01480)

