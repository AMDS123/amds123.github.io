---
layout: post
title: "Backprop as Functor: A compositional perspective on supervised learning"
date: 2019-05-01 15:11:06
categories: arXiv_AI
tags: arXiv_AI Gradient_Descent
author: Brendan Fong, David I. Spivak, R&#xe9;my Tuy&#xe9;ras
mathjax: true
---

* content
{:toc}

##### Abstract
A supervised learning algorithm searches over a set of functions $A \to B$ parametrised by a space $P$ to find the best approximation to some ideal function $f\colon A \to B$. It does this by taking examples $(a,f(a)) \in A\times B$, and updating the parameter according to some rule. We define a category where these update rules may be composed, and show that gradient descent---with respect to a fixed step size and an error function satisfying a certain property---defines a monoidal functor from a category of parametrised functions to this category of update rules. This provides a structural perspective on backpropagation, as well as a broad generalisation of neural networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.10455](http://arxiv.org/abs/1711.10455)

##### PDF
[http://arxiv.org/pdf/1711.10455](http://arxiv.org/pdf/1711.10455)

