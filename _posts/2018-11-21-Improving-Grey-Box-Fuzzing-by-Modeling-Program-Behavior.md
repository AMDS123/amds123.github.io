---
layout: post
title: "Improving Grey-Box Fuzzing by Modeling Program Behavior"
date: 2018-11-21 23:34:57
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Siddharth Karamcheti, Gideon Mann, David Rosenberg
mathjax: true
---

* content
{:toc}

##### Abstract
Grey-box fuzzers such as American Fuzzy Lop (AFL) are popular tools for finding bugs and potential vulnerabilities in programs. While these fuzzers have been able to find vulnerabilities in many widely used programs, they are not efficient; of the millions of inputs executed by AFL in a typical fuzzing run, only a handful discover unseen behavior or trigger a crash. The remaining inputs are redundant, exhibiting behavior that has already been observed. Here, we present an approach to increase the efficiency of fuzzers like AFL by applying machine learning to directly model how programs behave. We learn a forward prediction model that maps program inputs to execution traces, training on the thousands of inputs collected during standard fuzzing. This learned model guides exploration by focusing on fuzzing inputs on which our model is the most uncertain (measured via the entropy of the predicted execution trace distribution). By focusing on executing inputs our learned model is unsure about, and ignoring any input whose behavior our model is certain about, we show that we can significantly limit wasteful execution. Through testing our approach on a set of binaries released as part of the DARPA Cyber Grand Challenge, we show that our approach is able to find a set of inputs that result in more code coverage and discovered crashes than baseline fuzzers with significantly fewer executions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08973](http://arxiv.org/abs/1811.08973)

##### PDF
[http://arxiv.org/pdf/1811.08973](http://arxiv.org/pdf/1811.08973)

