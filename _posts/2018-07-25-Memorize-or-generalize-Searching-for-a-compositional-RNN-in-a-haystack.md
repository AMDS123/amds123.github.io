---
layout: post
title: "Memorize or generalize? Searching for a compositional RNN in a haystack"
date: 2018-07-25 18:55:27
categories: arXiv_CV
tags: arXiv_CV RNN Gradient_Descent
author: Adam Liška, Germán Kruszewski, Marco Baroni
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are very powerful learning systems, but they do not readily generalize from one task to the other. This is partly due to the fact that they do not learn in a compositional way, that is, by discovering skills that are shared by different tasks, and recombining them to solve new problems. In this paper, we explore the compositional generalization capabilities of recurrent neural networks (RNNs). We first propose the lookup table composition domain as a simple setup to test compositional behaviour and show that it is theoretically possible for a standard RNN to learn to behave compositionally in this domain when trained with standard gradient descent and provided with additional supervision. We then remove this additional supervision and perform a search over a large number of model initializations to investigate the proportion of RNNs that can still converge to a compositional solution. We discover that a small but non-negligible proportion of RNNs do reach partial compositional solutions even without special architectural constraints. This suggests that a combination of gradient descent and evolutionary strategies directly favouring the minority models that developed more compositional approaches might suffice to lead standard RNNs towards compositional solutions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.06467](https://arxiv.org/abs/1802.06467)

##### PDF
[https://arxiv.org/pdf/1802.06467](https://arxiv.org/pdf/1802.06467)

