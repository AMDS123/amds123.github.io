---
layout: post
title: "Learning to Optimize Computational Resources: Frugal Training with Generalization Guarantees"
date: 2019-05-26 15:43:50
categories: arXiv_AI
tags: arXiv_AI
author: Maria-Florina Balcan, Tuomas Sandholm, Ellen Vitercik
mathjax: true
---

* content
{:toc}

##### Abstract
Algorithms typically come with tunable parameters that have a considerable impact on the computational resources they consume. Too often, practitioners must hand-tune the parameters, a tedious and error-prone task. A recent line of research provides algorithms that return nearly-optimal parameters from within a finite set. These algorithms can be used when the parameter space is infinite by providing as input a random sample of parameters. This data-independent discretization, however, might miss pockets of nearly-optimal parameters: prior research has presented scenarios where the only viable parameters lie within an arbitrarily small region. We provide an algorithm that learns a finite set of promising parameters from within an infinite set. Our algorithm can help compile a configuration portfolio, or it can be used to select the input to a configuration algorithm for finite parameter spaces. Our approach applies to any configuration problem that satisfies a simple yet ubiquitous structure: the algorithm's performance is a piecewise constant function of its parameters. Prior research has exhibited this structure in domains from integer programming to clustering. For these types of combinatorial problems, this is the first configuration algorithm beyond exhaustive search whose output provably competes with the best parameters from an infinite space.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10819](http://arxiv.org/abs/1905.10819)

##### PDF
[http://arxiv.org/pdf/1905.10819](http://arxiv.org/pdf/1905.10819)

