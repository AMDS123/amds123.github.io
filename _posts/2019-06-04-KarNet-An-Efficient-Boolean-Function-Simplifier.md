---
layout: post
title: "KarNet: An Efficient Boolean Function Simplifier"
date: 2019-06-04 11:55:22
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Shanka Subhra Mondal, Abhilash Nandy, Ritesh Agrawal, Debashis Sen
mathjax: true
---

* content
{:toc}

##### Abstract
Many approaches such as Quine-McCluskey algorithm, Karnaugh map solving, Petrick's method and McBoole's method have been devised to simplify Boolean expressions in order to optimize hardware implementation of digital circuits. However, the algorithmic implementations of these methods are hard-coded and also their computation time is proportional to the number of minterms involved in the expression. In this paper, we propose KarNet, where the ability of Convolutional Neural Networks to model relationships between various cell locations and values by capturing spatial dependencies is exploited to solve Karnaugh maps. In order to do so, a Karnaugh map is represented as an image signal, where each cell is considered as a pixel. Experimental results show that the computation time of KarNet is independent of the number of minterms and is of the order of one-hundredth to one-tenth that of the rule-based methods. KarNet being a learned system is found to achieve nearly a hundred percent accuracy, precision, and recall. We train KarNet to solve four variable Karnaugh maps and also show that a similar method can be applied on Karnaugh maps with more variables. Finally, we show a way to build a fully accurate and computationally fast system using KarNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01363](http://arxiv.org/abs/1906.01363)

##### PDF
[http://arxiv.org/pdf/1906.01363](http://arxiv.org/pdf/1906.01363)

