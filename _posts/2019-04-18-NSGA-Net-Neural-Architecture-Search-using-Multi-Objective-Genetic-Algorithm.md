---
layout: post
title: "NSGA-Net: Neural Architecture Search using Multi-Objective Genetic Algorithm"
date: 2019-04-18 23:07:16
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Zhichao Lu, Ian Whalen, Vishnu Boddeti, Yashesh Dhebar, Kalyanmoy Deb, Erik Goodman, Wolfgang Banzhaf
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces NSGA-Net -- an evolutionary approach for neural architecture search (NAS). NSGA-Net is designed with three goals in mind: (1) a procedure considering multiple and conflicting objectives, (2) an efficient procedure balancing exploration and exploitation of the space of potential neural network architectures, and (3) a procedure finding a diverse set of trade-off network architectures achieved in a single run. NSGA-Net is a population-based search algorithm that explores a space of potential neural network architectures in three steps, namely, a population initialization step that is based on prior-knowledge from hand-crafted architectures, an exploration step comprising crossover and mutation of architectures, and finally an exploitation step that utilizes the hidden useful knowledge stored in the entire history of evaluated neural architectures in the form of a Bayesian Network. Experimental results suggest that combining the dual objectives of minimizing an error metric and computational complexity, as measured by FLOPs, allows NSGA-Net to find competitive neural architectures. Moreover, NSGA-Net achieves error rate on the CIFAR-10 dataset on par with other state-of-the-art NAS methods while using orders of magnitude less computational resources. These results are encouraging and shows the promise to further use of EC methods in various deep-learning paradigms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.03522](http://arxiv.org/abs/1810.03522)

##### PDF
[http://arxiv.org/pdf/1810.03522](http://arxiv.org/pdf/1810.03522)

