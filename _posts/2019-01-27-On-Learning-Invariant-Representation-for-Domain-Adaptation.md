---
layout: post
title: "On Learning Invariant Representation for Domain Adaptation"
date: 2019-01-27 22:44:00
categories: arXiv_AI
tags: arXiv_AI Represenation_Learning
author: Han Zhao, Remi Tachet des Combes, Kun Zhang, Geoffrey J. Gordon
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the ability of deep neural nets to learn rich representations, recent advances in unsupervised domain adaptation have focused on learning domain-invariant features that achieve a small error on the source domain. The hope is that the learnt representation, together with the hypothesis learnt from the source domain, can generalize to the target domain. In this paper, we first construct a simple counterexample showing that, contrary to common belief, the above conditions are not sufficient to guarantee successful domain adaptation. In particular, the counterexample (Fig. 1) exhibits \emph{conditional shift}: the class-conditional distributions of input features change between source and target domains. To give a sufficient condition for domain adaptation, we propose a natural and interpretable generalization upper bound that explicitly takes into account the aforementioned shift. Moreover, we shed new light on the problem by proving an information-theoretic lower bound on the joint error of \emph{any} domain adaptation method that attempts to learn invariant representations. Our result characterizes a fundamental tradeoff between learning invariant representations and achieving small joint error on both domains when the marginal label distributions differ from source to target. Finally, we conduct experiments on real-world datasets that corroborate our theoretical findings. We believe these insights are helpful in guiding the future design of domain adaptation and representation learning algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09453](http://arxiv.org/abs/1901.09453)

##### PDF
[http://arxiv.org/pdf/1901.09453](http://arxiv.org/pdf/1901.09453)

