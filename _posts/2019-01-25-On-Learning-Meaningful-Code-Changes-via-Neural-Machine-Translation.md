---
layout: post
title: "On Learning Meaningful Code Changes via Neural Machine Translation"
date: 2019-01-25 22:12:39
categories: arXiv_CL
tags: arXiv_CL NMT Deep_Learning Quantitative
author: Michele Tufano, Jevgenija Pantiuchina, Cody Watson, Gabriele Bavota, Denys Poshyvanyk
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have seen the rise of Deep Learning (DL) techniques applied to source code. Researchers have exploited DL to automate several development and maintenance tasks, such as writing commit messages, generating comments and detecting vulnerabilities among others. One of the long lasting dreams of applying DL to source code is the possibility to automate non-trivial coding activities. While some steps in this direction have been taken (e.g., learning how to fix bugs), there is still a glaring lack of empirical evidence on the types of code changes that can be learned and automatically applied by DL. Our goal is to make this first important step by quantitatively and qualitatively investigating the ability of a Neural Machine Translation (NMT) model to learn how to automatically apply code changes implemented by developers during pull requests. We train and experiment with the NMT model on a set of 236k pairs of code components before and after the implementation of the changes provided in the pull requests. We show that, when applied in a narrow enough context (i.e., small/medium-sized pairs of methods before/after the pull request changes), NMT can automatically replicate the changes implemented by developers during pull requests in up to 36% of the cases. Moreover, our qualitative analysis shows that the model is capable of learning and replicating a wide variety of meaningful code changes, especially refactorings and bug-fixing activities. Our results pave the way for novel research in the area of DL on code, such as the automatic learning and applications of refactoring.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09102](http://arxiv.org/abs/1901.09102)

##### PDF
[http://arxiv.org/pdf/1901.09102](http://arxiv.org/pdf/1901.09102)

