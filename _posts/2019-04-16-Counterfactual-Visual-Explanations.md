---
layout: post
title: "Counterfactual Visual Explanations"
date: 2019-04-16 04:16:11
categories: arXiv_AI
tags: arXiv_AI Image_Classification Classification
author: Yash Goyal, Ziyan Wu, Jan Ernst, Dhruv Batra, Devi Parikh, Stefan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
A counterfactual query is typically of the form 'For situation X, why was the outcome Y and not Z?'. A counterfactual explanation (or response to such a query) is of the form "If X was X*, then the outcome would have been Z rather than Y." 
 In this work, we develop a technique to produce counterfactual visual explanations. Given a 'query' image $I$ for which a vision system predicts class $c$, a counterfactual visual explanation identifies how $I$ could change such that the system would output a different specified class $c'$. To do this, we select a 'distractor' image $I'$ that the system predicts as class $c'$ and identify spatial regions in $I$ and $I'$ such that replacing the identified region in $I$ with the identified region in $I'$ would push the system towards classifying $I$ as $c'$. 
 We apply our approach to multiple image classification datasets generating qualitative results showcasing the interpretability and discriminativeness of our counterfactual explanations. To explore the effectiveness of our explanations in teaching humans, we present machine teaching experiments for the task of fine-grained bird classification. We find that users trained to distinguish bird species fare better when given access to counterfactual explanations in addition to training examples.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07451](http://arxiv.org/abs/1904.07451)

##### PDF
[http://arxiv.org/pdf/1904.07451](http://arxiv.org/pdf/1904.07451)

