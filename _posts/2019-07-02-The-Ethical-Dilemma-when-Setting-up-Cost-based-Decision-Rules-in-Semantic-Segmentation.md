---
layout: post
title: "The Ethical Dilemma when Setting up Cost-based Decision Rules in Semantic Segmentation"
date: 2019-07-02 13:17:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Robin Chan, Matthias Rottmann, Radin Dardashti, Fabian H&#xfc;ger, Peter Schlicht, Hanno Gottschalk
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks for semantic segmentation can be seen as statistical models that provide for each pixel of one image a probability distribution on predefined classes. The predicted class is then usually obtained by the maximum a-posteriori probability (MAP) which is known as Bayes rule in decision theory. From decision theory we also know that the Bayes rule is optimal regarding the simple symmetric cost function. Therefore, it weights each type of confusion between two different classes equally, e.g., given images of urban street scenes there is no distinction in the cost function if the network confuses a person with a street or a building with a tree. Intuitively, there might be confusions of classes that are more important to avoid than others. In this work, we want to raise awareness of the possibility of explicitly defining confusion costs and the associated ethical difficulties if it comes down to providing numbers. We define two cost functions from different extreme perspectives, an egoistic and an altruistic one, and show how safety relevant quantities like precision / recall and (segment-wise) false positive / negative rate change when interpolating between MAP, egoistic and altruistic decision rules.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01342](http://arxiv.org/abs/1907.01342)

##### PDF
[http://arxiv.org/pdf/1907.01342](http://arxiv.org/pdf/1907.01342)

