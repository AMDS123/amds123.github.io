---
layout: post
title: "What you get is what you see: Decomposing Epistemic Planning using Functional STRIPS"
date: 2019-03-28 03:34:45
categories: arXiv_AI
tags: arXiv_AI Knowledge Relation
author: Guang Hu, Tim Miller, Nir Lipovetzky
mathjax: true
---

* content
{:toc}

##### Abstract
Epistemic planning --- planning with knowledge and belief --- is essential in many multi-agent and human-agent interaction domains. Most state-of-the-art epistemic planners solve this problem by compiling to propositional classical planning, for example, generating all possible knowledge atoms, or compiling epistemic formula to normal forms. However, these methods become computationally infeasible as problems grow. In this paper, we decompose epistemic planning by delegating reasoning about epistemic formula to an external solver. We do this by modelling the problem using \emph{functional STRIPS}, which is more expressive than standard STRIPS and supports the use of external, black-box functions within action models. Exploiting recent work that demonstrates the relationship between what an agent `sees' and what it knows, we allow modellers to provide new implementations of externals functions. These define what agents see in their environment, allowing new epistemic logics to be defined without changing the planner. As a result, it increases the capability and flexibility of the epistemic model itself, and avoids the exponential pre-compilation step. We ran evaluations on well-known epistemic planning benchmarks to compare with an existing state-of-the-art planner, and on new scenarios based on different external functions. The results show that our planner scales significantly better than the state-of-the-art planner against which we compared, and can express problems more succinctly.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11777](http://arxiv.org/abs/1903.11777)

##### PDF
[http://arxiv.org/pdf/1903.11777](http://arxiv.org/pdf/1903.11777)

