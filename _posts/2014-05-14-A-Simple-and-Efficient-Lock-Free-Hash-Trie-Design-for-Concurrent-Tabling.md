---
layout: post
title: "A Simple and Efficient Lock-Free Hash Trie Design for Concurrent Tabling"
date: 2014-05-14 17:02:45
categories: arXiv_CV
tags: arXiv_CV
author: Miguel Areias, Ricardo Rocha
mathjax: true
---

* content
{:toc}

##### Abstract
A critical component in the implementation of a concurrent tabling system is the design of the table space. One of the most successful proposals for representing tables is based on a two-level trie data structure, where one trie level stores the tabled subgoal calls and the other stores the computed answers. In this work, we present a simple and efficient lock-free design where both levels of the tries can be shared among threads in a concurrent environment. To implement lock-freedom we took advantage of the CAS atomic instruction that nowadays can be widely found on many common architectures. CAS reduces the granularity of the synchronization when threads access concurrent areas, but still suffers from low-level problems such as false sharing or cache memory side-effects. In order to be as effective as possible in the concurrent search and insert operations over the table space data structures, we based our design on a hash trie data structure in such a way that it minimizes potential low-level synchronization problems by dispersing as much as possible the concurrent areas. Experimental results in the Yap Prolog system show that our new lock-free hash trie design can effectively reduce the execution time and scale better than previous designs.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1405.2850](https://arxiv.org/abs/1405.2850)

##### PDF
[https://arxiv.org/pdf/1405.2850](https://arxiv.org/pdf/1405.2850)

