---
layout: post
title: "Open-world Learning and Application to Product Classification"
date: 2019-03-01 23:25:46
categories: arXiv_AI
tags: arXiv_AI Classification
author: Hu Xu, Bing Liu, Lei Shu, P. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Classic supervised learning makes the closed-world assumption, meaning that classes seen in testing must have been seen in training. However, in the dynamic world, new or unseen class examples may appear constantly. A model working in such an environment must be able to reject unseen classes (not seen or used in training). If enough data is collected for the unseen classes, the system should incrementally learn to accept/classify them. This learning paradigm is called open-world learning (OWL). Existing OWL methods all need some form of re-training to accept or include the new classes in the overall model. In this paper, we propose a meta-learning approach to the problem. Its key novelty is that it only needs to train a meta-classifier, which can then continually accept new classes when they have enough labeled data for the meta-classifier to use, and also detect/reject future unseen classes. No re-training of the meta-classifier or a new overall classifier covering all old and new classes is needed. In testing, the method only uses the examples of the seen classes (including the newly added classes) on-the-fly for classification and rejection. Experimental results demonstrate the effectiveness of the new approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.06004](http://arxiv.org/abs/1809.06004)

##### PDF
[http://arxiv.org/pdf/1809.06004](http://arxiv.org/pdf/1809.06004)

