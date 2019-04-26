---
layout: post
title: "Characterization of Glue Variables in CDCL SAT Solving"
date: 2019-04-25 00:52:06
categories: arXiv_AI
tags: arXiv_AI Inference
author: Md Solimul Chowdhury, Martin M&#xfc;ller, Jia-Huai You
mathjax: true
---

* content
{:toc}

##### Abstract
A state-of-the-art criterion to evaluate the importance of a given learned clause is called Literal Block Distance (LBD) score. It measures the number of distinct decision levels in a given learned clause. The lower the LBD score of a learned clause, the better is its quality. The learned clauses with LBD score of 2, called glue clauses, are known to possess high pruning power which are never deleted from the clause databases of the modern CDCL SAT solvers. In this work, we relate glue clauses to decision variables. We call the variables that appeared in at least one glue clause up to the current search state Glue Variables. We first show experimentally, by running the state-of-the-art CDCL SAT solver MapleLCMDist on benchmarks from SAT Competition-2017 and 2018, that branching decisions with glue variables are categorically more inference and conflict efficient than nonglue variables. Based on this observation, we develop a structure aware CDCL variable bumping scheme, which bumps the activity score of a glue variable based on its appearance count in the glue clauses that are learned so far by the search. Empirical evaluation shows effectiveness of the new method over the main track instances from SAT Competition 2017 and 2018.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11106](http://arxiv.org/abs/1904.11106)

##### PDF
[http://arxiv.org/pdf/1904.11106](http://arxiv.org/pdf/1904.11106)

