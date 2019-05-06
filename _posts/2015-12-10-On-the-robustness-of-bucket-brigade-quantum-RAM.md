---
layout: post
title: "On the robustness of bucket brigade quantum RAM"
date: 2015-12-10 19:26:46
categories: arXiv_CV
tags: arXiv_CV
author: Srinivasan Arunachalam, Vlad Gheorghiu, Tomas Jochym-O'Connor, Michele Mosca, Priyaa Varshinee Srinivasan
mathjax: true
---

* content
{:toc}

##### Abstract
We study the robustness of the bucket brigade quantum random access memory model introduced by Giovannetti, Lloyd, and Maccone [Phys. Rev. Lett. 100, 160501 (2008)]. Due to a result of Regev and Schiff [ICALP '08 pp. 773], we show that for a class of error models the error rate per gate in the bucket brigade quantum memory has to be of order $o(2^{-n/2})$ (where $N=2^n$ is the size of the memory) whenever the memory is used as an oracle for the quantum searching problem. We conjecture that this is the case for any realistic error model that will be encountered in practice, and that for algorithms with super-polynomially many oracle queries the error rate must be super-polynomially small, which further motivates the need for quantum error correction. By contrast, for algorithms such as matrix inversion [Phys. Rev. Lett. 103, 150502 (2009)] or quantum machine learning [Phys. Rev. Lett. 113, 130503 (2014)] that only require a polynomial number of queries, the error rate only needs to be polynomially small and quantum error correction may not be required. We introduce a circuit model for the quantum bucket brigade architecture and argue that quantum error correction for the circuit causes the quantum bucket brigade architecture to lose its primary advantage of a small number of "active" gates, since all components have to be actively error corrected.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1502.03450](https://arxiv.org/abs/1502.03450)

##### PDF
[https://arxiv.org/pdf/1502.03450](https://arxiv.org/pdf/1502.03450)

