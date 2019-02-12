---
layout: post
title: "Task2Vec: Task Embedding for Meta-Learning"
date: 2019-02-10 06:27:25
categories: arXiv_AI
tags: arXiv_AI Embedding Classification Relation
author: Alessandro Achille, Michael Lam, Rahul Tewari, Avinash Ravichandran, Subhransu Maji, Charless Fowlkes, Stefano Soatto, Pietro Perona
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a method to provide vectorial representations of visual classification tasks which can be used to reason about the nature of those tasks and their relations. Given a dataset with ground-truth labels and a loss function defined over those labels, we process images through a "probe network" and compute an embedding based on estimates of the Fisher information matrix associated with the probe network parameters. This provides a fixed-dimensional embedding of the task that is independent of details such as the number of classes and does not require any understanding of the class label semantics. We demonstrate that this embedding is capable of predicting task similarities that match our intuition about semantic and taxonomic relations between different visual tasks (e.g., tasks based on classifying different types of plants are similar) We also demonstrate the practical value of this framework for the meta-task of selecting a pre-trained feature extractor for a new task. We present a simple meta-learning framework for learning a metric on embeddings that is capable of predicting which feature extractors will perform well. Selecting a feature extractor with task embedding obtains a performance close to the best available feature extractor, while costing substantially less than exhaustively training and evaluating on all available feature extractors.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03545](http://arxiv.org/abs/1902.03545)

##### PDF
[http://arxiv.org/pdf/1902.03545](http://arxiv.org/pdf/1902.03545)

