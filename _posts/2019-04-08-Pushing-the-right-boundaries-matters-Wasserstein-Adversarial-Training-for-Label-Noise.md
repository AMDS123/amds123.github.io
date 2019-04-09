---
layout: post
title: "Pushing the right boundaries matters! Wasserstein Adversarial Training for Label Noise"
date: 2019-04-08 10:28:12
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Segmentation Semantic_Segmentation Classification Relation
author: Bharath Bhushan Damodaran, Kilian Fatras, Sylvain Lobry, R&#xe9;mi Flamary, Devis Tuia, Nicolas Courty
mathjax: true
---

* content
{:toc}

##### Abstract
Noisy labels often occur in vision datasets, especially when they are issued from crowdsourcing or Web scraping. In this paper, we propose a new regularization method which enables one to learn robust classifiers in presence of noisy data. To achieve this goal, we augment the virtual adversarial loss with a Wasserstein distance. This distance allows us to take into account specific relations between classes by leveraging on the geometric properties of this optimal transport distance. Notably, we encode the class similarities in the ground cost that is used to compute the Wasserstein distance. As a consequence, we can promote smoothness between classes that are very dissimilar, while keeping the classification decision function sufficiently complex for similar classes. While designing this ground cost can be left as a problem-specific modeling task, we show in this paper that using the semantic relations between classes names already leads to good results.Our proposed Wasserstein Adversarial Training (WAT) outperforms state of the art on four datasets corrupted with noisy labels: three classical benchmarks and one real case in remote sensing image semantic segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03936](http://arxiv.org/abs/1904.03936)

##### PDF
[http://arxiv.org/pdf/1904.03936](http://arxiv.org/pdf/1904.03936)

