---
layout: post
title: "Separators and Adjustment Sets in Causal Graphs: Complete Criteria and an Algorithmic Framework"
date: 2019-01-24 16:33:53
categories: arXiv_AI
tags: arXiv_AI
author: Benito van der Zander (1), Maciej Li&#x15b;kiewicz (1), Johannes Textor (2) ((1) Institute for Theoretical Computer Science, Universit&#xe4;t zu L&#xfc;beck, Germany, (2) Institute for Computing and Information Sciences, Radboud University Nijmegen, Nijmegen, The Netherlands)
mathjax: true
---

* content
{:toc}

##### Abstract
Principled reasoning about the identifiability of causal effects from non-experimental data is an important application of graphical causal models. This paper focuses on effects that are identifiable by covariate adjustment, a commonly used estimation approach. We present an algorithmic framework for efficiently testing, constructing, and enumerating $m$-separators in ancestral graphs (AGs), a class of graphical causal models that can represent uncertainty about the presence of latent confounders. Furthermore, we prove a reduction from causal effect identification by covariate adjustment to $m$-separation in a subgraph for directed acyclic graphs (DAGs) and maximal ancestral graphs (MAGs). Jointly, these results yield constructive criteria that characterize all adjustment sets as well as all minimal and minimum adjustment sets for identification of a desired causal effect with multivariate exposures and outcomes in the presence of latent confounding. Our results extend several existing solutions for special cases of these problems. Our efficient algorithms allowed us to empirically quantify the identifiability gap between covariate adjustment and the do-calculus in random DAGs and MAGs, covering a wide range of scenarios. Implementations of our algorithms are provided in the R package dagitty.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.00116](http://arxiv.org/abs/1803.00116)

##### PDF
[http://arxiv.org/pdf/1803.00116](http://arxiv.org/pdf/1803.00116)

