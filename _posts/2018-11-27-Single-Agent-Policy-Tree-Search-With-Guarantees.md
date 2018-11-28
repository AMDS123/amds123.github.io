---
layout: post
title: "Single-Agent Policy Tree Search With Guarantees"
date: 2018-11-27 11:53:33
categories: arXiv_AI
tags: arXiv_AI
author: Laurent Orseau, Levi H. S. Lelis, Tor Lattimore, Th&#xe9;ophane Weber
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce two novel tree search algorithms that use a policy to guide search. The first algorithm is a best-first enumeration that uses a cost function that allows us to prove an upper bound on the number of nodes to be expanded before reaching a goal state. We show that this best-first algorithm is particularly well suited for `needle-in-a-haystack' problems. The second algorithm is based on sampling and we prove an upper bound on the expected number of nodes it expands before reaching a set of goal states. We show that this algorithm is better suited for problems where many paths lead to a goal. We validate these tree search algorithms on 1,000 computer-generated levels of Sokoban, where the policy used to guide the search comes from a neural network trained using A3C. Our results show that the policy tree search algorithms we introduce are competitive with a state-of-the-art domain-independent planner that uses heuristic search.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10928](http://arxiv.org/abs/1811.10928)

##### PDF
[http://arxiv.org/pdf/1811.10928](http://arxiv.org/pdf/1811.10928)

