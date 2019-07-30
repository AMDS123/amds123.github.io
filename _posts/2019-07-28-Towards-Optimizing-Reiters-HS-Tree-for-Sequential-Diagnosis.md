---
layout: post
title: "Towards Optimizing Reiter's HS-Tree for Sequential Diagnosis"
date: 2019-07-28 19:26:08
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Patrick Rodler
mathjax: true
---

* content
{:toc}

##### Abstract
Reiter's HS-Tree is one of the most popular diagnostic search algorithms due to its desirable properties and general applicability. In sequential diagnosis, where the addressed diagnosis problem is subject to successive change through the acquisition of additional knowledge about the diagnosed system, HS-Tree is used in a stateless fashion. That is, the existing search tree is discarded when new knowledge is obtained, albeit often large parts of the tree are still relevant and have to be rebuilt in the next iteration, involving redundant operations and costly reasoner calls. As a remedy to this, we propose DynamicHS, a variant of HS-Tree that avoids these redundancy issues by maintaining state throughout sequential diagnosis while preserving all desirable properties of HS-Tree. Preliminary results of ongoing evaluations in a problem domain where HS-Tree is the state-of-the-art diagnostic method suggest significant time savings achieved by DynamicHS by reducing expensive reasoner calls.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12130](http://arxiv.org/abs/1907.12130)

##### PDF
[http://arxiv.org/pdf/1907.12130](http://arxiv.org/pdf/1907.12130)

