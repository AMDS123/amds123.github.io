---
layout: post
title: "State-Reification Networks: Improving Generalization by Modeling the Distribution of Hidden Representations"
date: 2019-05-26 09:13:41
categories: arXiv_AI
tags: arXiv_AI Adversarial Sparse
author: Alex Lamb, Jonathan Binas, Anirudh Goyal, Sandeep Subramanian, Ioannis Mitliagkas, Denis Kazakov, Yoshua Bengio, Michael C. Mozer
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning promises methods that generalize well from finite labeled data. However, the brittleness of existing neural net approaches is revealed by notable failures, such as the existence of adversarial examples that are misclassified despite being nearly identical to a training example, or the inability of recurrent sequence-processing nets to stay on track without teacher forcing. We introduce a method, which we refer to as \emph{state reification}, that involves modeling the distribution of hidden states over the training data and then projecting hidden states observed during testing toward this distribution. Our intuition is that if the network can remain in a familiar manifold of hidden space, subsequent layers of the net should be well trained to respond appropriately. We show that this state-reification method helps neural nets to generalize better, especially when labeled data are sparse, and also helps overcome the challenge of achieving robust generalization with adversarial training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.11382](http://arxiv.org/abs/1905.11382)

##### PDF
[http://arxiv.org/pdf/1905.11382](http://arxiv.org/pdf/1905.11382)

