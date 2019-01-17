---
layout: post
title: "Soft Constraints for Inference with Declarative Knowledge"
date: 2019-01-16 18:59:38
categories: arXiv_AI
tags: arXiv_AI Knowledge Inference
author: Zenna Tavares, Javier Burroni, Edgar Minaysan, Armando Solar Lezama, Rajesh Ranganath
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a likelihood free inference procedure for conditioning a probabilistic model on a predicate. A predicate is a Boolean valued function which expresses a yes/no question about a domain. Our contribution, which we call predicate exchange, constructs a softened predicate which takes value in the unit interval [0, 1] as opposed to a simply true or false. Intuitively, 1 corresponds to true, and a high value (such as 0.999) corresponds to "nearly true" as determined by a distance metric. We define Boolean algebra for soft predicates, such that they can be negated, conjoined and disjoined arbitrarily. A softened predicate can serve as a tractable proxy to a likelihood function for approximate posterior inference. However, to target exact inference, we temper the relaxation by a temperature parameter, and add a accept/reject phase use to replica exchange Markov Chain Mont Carlo, which exchanges states between a sequence of models conditioned on predicates at varying temperatures. We describe a lightweight implementation of predicate exchange that it provides a language independent layer that can be implemented on top of existingn modeling formalisms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.05437](http://arxiv.org/abs/1901.05437)

##### PDF
[http://arxiv.org/pdf/1901.05437](http://arxiv.org/pdf/1901.05437)

