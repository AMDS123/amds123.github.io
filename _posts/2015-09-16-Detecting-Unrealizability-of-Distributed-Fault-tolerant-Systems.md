---
layout: post
title: "Detecting Unrealizability of Distributed Fault-tolerant Systems"
date: 2015-09-16 17:15:41
categories: arXiv_CV
tags: arXiv_CV Detection
author: Bernd Finkbeiner (Saarland University), Leander Tentrup (Saarland University)
mathjax: true
---

* content
{:toc}

##### Abstract
Writing formal specifications for distributed systems is difficult. Even simple consistency requirements often turn out to be unrealizable because of the complicated information flow in the distributed system: not all information is available in every component, and information transmitted from other components may arrive with a delay or not at all, especially in the presence of faults. The problem of checking the distributed realizability of a temporal specification is, in general, undecidable. Semi-algorithms for synthesis, such as bounded synthesis, are only useful in the positive case, where they construct an implementation for a realizable specification, but not in the negative case: if the specification is unrealizable, the search for the implementation never terminates. In this paper, we introduce counterexamples to distributed realizability and present a method for the detection of such counterexamples for specifications given in linear-time temporal logic (LTL). A counterexample consists of a set of paths, each representing a different sequence of inputs from the environment, such that, no matter how the components are implemented, the specification is violated on at least one of these paths. We present a method for finding such counterexamples both for the classic distributed realizability problem and for the fault-tolerant realizability problem. Our method considers, incrementally, larger and larger sets of paths until a counterexample is found. For safety specifications in weakly ordered architectures we obtain a decision procedure, while counterexamples for full LTL and arbitrary architectures may consist of infinitely many paths. Experimental results, obtained with a QBF-based prototype implementation, show that our method finds simple errors very quickly, and even problems with high combinatorial complexity, like the Byzantine Generals' Problem, are tractable.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1505.06862](https://arxiv.org/abs/1505.06862)

##### PDF
[https://arxiv.org/pdf/1505.06862](https://arxiv.org/pdf/1505.06862)

