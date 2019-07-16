---
layout: post
title: "MIPaaL: Mixed Integer Program as a Layer"
date: 2019-07-12 18:22:09
categories: arXiv_AI
tags: arXiv_AI Optimization Prediction
author: Aaron Ferber, Bryan Wilder, Bistra Dilina, Milind Tambe
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning components commonly appear in larger decision-making pipelines; however, the model training process typically focuses only on a loss that measures accuracy between predicted values and ground truth values. Decision-focused learning explicitly integrates the downstream decision problem when training the predictive model, in order to optimize the quality of decisions induced by the predictions. It has been successfully applied to several limited combinatorial problem classes, such as those that can be expressed as linear programs (LP), and submodular optimization. However, these previous applications have uniformly focused on problems from specific classes with simple constraints. Here, we enable decision-focused learning for the broad class of problems that can be encoded as a Mixed Integer Linear Program (MIP), hence supporting arbitrary linear constraints over discrete and continuous variables. We show how to differentiate through a MIP by employing a cutting planes solution approach, which is an exact algorithm that iteratively adds constraints to a continuous relaxation of the problem until an integral solution is found. We evaluate our new end-to-end approach on several real world domains and show that it outperforms the standard two phase approaches that treat prediction and prescription separately, as well as a baseline approach of simply applying decision-focused learning to the LP relaxation of the MIP.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05912](http://arxiv.org/abs/1907.05912)

##### PDF
[http://arxiv.org/pdf/1907.05912](http://arxiv.org/pdf/1907.05912)

