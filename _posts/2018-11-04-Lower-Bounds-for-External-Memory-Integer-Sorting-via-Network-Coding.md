---
layout: post
title: "Lower Bounds for External Memory Integer Sorting via Network Coding"
date: 2018-11-04 02:41:43
categories: arXiv_CV
tags: arXiv_CV
author: Alireza Farhadi, MohammadTaghi Hajiaghayi, Kasper Green Larsen, Elaine Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Sorting extremely large datasets is a frequently occuring task in practice. These datasets are usually much larger than the computer's main memory; thus external memory sorting algorithms, first introduced by Aggarwal and Vitter (1988), are often used. The complexity of comparison based external memory sorting has been understood for decades by now, however the situation remains elusive if we assume the keys to be sorted are integers. In internal memory, one can sort a set of $n$ integer keys of $Θ(\lg n)$ bits each in $O(n)$ time using the classic Radix Sort algorithm, however in external memory, there are no faster integer sorting algorithms known than the simple comparison based ones. In this paper, we present a tight conditional lower bound on the complexity of external memory sorting of integers. Our lower bound is based on a famous conjecture in network coding by Li and Li, who conjectured that network coding cannot help anything beyond the standard multicommodity flow rate in undirected graphs. The only previous work connecting the Li and Li conjecture to lower bounds for algorithms is due to Adler et al. Adler et al. indeed obtain relatively simple lower bounds for oblivious algorithms (the memory access pattern is fixed and independent of the input data). Unfortunately obliviousness is a strong limitations, especially for integer sorting: we show that the Li and Li conjecture implies an $Ω(n \log n)$ lower bound for internal memory oblivious sorting when the keys are $Θ(\lg n)$ bits. This is in sharp contrast to the classic (non-oblivious) Radix Sort algorithm. Indeed going beyond obliviousness is highly non-trivial; we need to introduce several new methods and involved techniques, which are of their own interest, to obtain our tight lower bound for external memory integer sorting.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.01313](https://arxiv.org/abs/1811.01313)

##### PDF
[https://arxiv.org/pdf/1811.01313](https://arxiv.org/pdf/1811.01313)

