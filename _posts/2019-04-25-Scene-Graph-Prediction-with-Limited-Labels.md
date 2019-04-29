---
layout: post
title: "Scene Graph Prediction with Limited Labels"
date: 2019-04-25 23:26:25
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Caption Transfer_Learning Prediction Relation VQA
author: Vincent S. Chen, Paroma Varma, Ranjay Krishna, Michael Bernstein, Christopher Re, Li Fei-Fei
mathjax: true
---

* content
{:toc}

##### Abstract
Visual knowledge bases such as Visual Genome power numerous applications in computer vision, including visual question answering and captioning, but suffer from sparse, incomplete relationships. All scene graph models to date are limited to training on a small set of visual relationships that have thousands of training labels each. Hiring human annotators is expensive, and using textual knowledge base completion methods are incompatible with visual data. In this paper, we introduce a semi-supervised method that assigns probabilistic relationship labels to a large number of unlabeled images using few labeled examples. We analyze visual relationships to suggest two types of image-agnostic features that are used to generate noisy heuristics, whose outputs are aggregated using a factor graph-based generative model. With as few as 10 labeled relationship examples, the generative model creates enough training data to train any existing state-of-the-art scene graph model. We demonstrate that our method for generating training data outperforms all baseline approaches by 5.16 recall@100. Since we only use a few labels, we define a complexity metric for relationships that serves as an indicator (R^2 = 0.778) for conditions under which our method succeeds over transfer learning, the de-facto approach for training with limited labels.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11622](http://arxiv.org/abs/1904.11622)

##### PDF
[http://arxiv.org/pdf/1904.11622](http://arxiv.org/pdf/1904.11622)

