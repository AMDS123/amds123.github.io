---
layout: post
title: "Intent Detection and Slots Prompt in a Closed-Domain Chatbot"
date: 2018-12-27 05:14:49
categories: arXiv_AI
tags: arXiv_AI QA Classification Detection
author: Amber Nigam, Prashik Sahare, Kushagra Pandya
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a methodology for predicting intent and slots of a query for a chatbot that answers career-related queries. We take a multi-staged approach where both the processes (intent-classification and slot-tagging) inform each other's decision-making in different stages. The model breaks down the problem into stages, solving one problem at a time and passing on relevant results of the current stage to the next, thereby reducing search space for subsequent stages, and eventually making classification and tagging more viable after each stage. We also observe that relaxing rules for a fuzzy entity-matching in slot-tagging after each stage (by maintaining a separate Named Entity Tagger per stage) helps us improve performance, although at a slight cost of false-positives. Our model has achieved state-of-the-art performance with F1-score of 77.63% for intent-classification and 82.24% for slot-tagging on our dataset that we would publicly release along with the paper.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10628](http://arxiv.org/abs/1812.10628)

##### PDF
[http://arxiv.org/pdf/1812.10628](http://arxiv.org/pdf/1812.10628)

