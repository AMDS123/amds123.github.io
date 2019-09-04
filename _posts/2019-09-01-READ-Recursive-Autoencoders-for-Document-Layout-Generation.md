---
layout: post
title: "READ: Recursive Autoencoders for Document Layout Generation"
date: 2019-09-01 01:58:31
categories: arXiv_CV
tags: arXiv_CV Detection
author: Akshay Gadi Patil, Omri Ben-Eliezer, Or Perel, Hadar Averbuch-Elor
mathjax: true
---

* content
{:toc}

##### Abstract
Layout is a fundamental component of any graphic design. Creating large varieties of plausible document layouts can be a tedious task, requiring numerous constraints to be satisfied, including local ones relating different semantic elements and global constraints on the general appearance and spacing. In this paper, we present a novel framework, coined READ, for REcursive Autoencoders for Document layout generation, to generate plausible 2D layouts of documents in large quantities and varieties. First, we devise an exploratory recursive method to extract a structural decomposition of a single document. Leveraging a dataset of documents annotated with labeled bounding boxes, our recursive neural network learns to map the structural representation, given in the form of a simple hierarchy, to a compact code, the space of which is approximated by a Gaussian distribution. Novel hierarchies can be sampled from this space, obtaining new document layouts. Moreover, we introduce a combinatorial metric to measure structural similarity among document layouts. We deploy it to show that our method is able to generate highly variable and realistic layouts. We further demonstrate the utility of our generated layouts in the context of standard detection tasks on documents, showing that detection performance improves when the training data is augmented with generated documents whose layouts are produced by READ.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00302](http://arxiv.org/abs/1909.00302)

##### PDF
[http://arxiv.org/pdf/1909.00302](http://arxiv.org/pdf/1909.00302)

