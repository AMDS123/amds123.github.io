---
layout: post
title: "Predicting Variable Types in Dynamically Typed Programming Languages"
date: 2019-01-16 05:42:22
categories: arXiv_AI
tags: arXiv_AI RNN
author: Abhinav Jangda, Gaurav Anand
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic Programming Languages are quite popular because they increase the programmer's productivity. However, the absence of types in the source code makes the program written in these languages difficult to understand and virtual machines that execute these programs cannot produced optimized code. To overcome this challenge, we develop a technique to predict types of all identifiers including variables, and function return types. 
 We propose the first implementation of $2^{nd}$ order Inside Outside Recursive Neural Networks with two variants (i) Child-Sum Tree-LSTMs and (ii) N-ary RNNs that can handle large number of tree branching. We predict the types of all the identifiers given the Abstract Syntax Tree by performing just two passes over the tree, bottom-up and top-down, keeping both the content and context representation for all the nodes of the tree. This allows these representations to interact by combining different paths from the parent, siblings and children which is crucial for predicting types. Our best model achieves 44.33\% across 21 classes and top-3 accuracy of 71.5\% on our gathered Python data set from popular Python benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.05138](http://arxiv.org/abs/1901.05138)

##### PDF
[http://arxiv.org/pdf/1901.05138](http://arxiv.org/pdf/1901.05138)

