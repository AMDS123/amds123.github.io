---
layout: post
title: "Formal Verification of Decision-Tree Ensemble Model and Detection of its Violating-input-value Ranges"
date: 2019-04-26 10:38:01
categories: arXiv_AI
tags: arXiv_AI Detection
author: Naoto Sato, Hironobu Kuruma, Yuichiroh Nakagawa, Hideto Ogawa
mathjax: true
---

* content
{:toc}

##### Abstract
As one type of machine-learning model, a "decision-tree ensemble model" (DTEM) is represented by a set of decision trees. A DTEM is mainly known to be valid for structured data; however, like other machine-learning models, it is difficult to train so that it returns the correct output value for any input value. Accordingly, when a DTEM is used in regard to a system that requires reliability, it is important to comprehensively detect input values that lead to malfunctions of a system (failures) during development and take appropriate measures. One conceivable solution is to install an input filter that controls the input to the DTEM, and to use separate software to process input values that may lead to failures. To develop the input filter, it is necessary to specify the filtering condition of the input value that leads to the malfunction of the system. Given that necessity, in this paper, we propose a method for formally verifying a DTEM and, according to the result of the verification, if an input value leading to a failure is found, extracting the range in which such an input value exists. The proposed method can comprehensively extract the range in which the input value leading to the failure exists; therefore, by creating an input filter based on that range, it is possible to prevent the failure occurring in the system. In this paper, the algorithm of the proposed method is described, and the results of a case study using a dataset of house prices are presented. On the basis of those results, the feasibility of the proposed method is demonstrated, and its scalability is evaluated.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11753](http://arxiv.org/abs/1904.11753)

##### PDF
[http://arxiv.org/pdf/1904.11753](http://arxiv.org/pdf/1904.11753)

