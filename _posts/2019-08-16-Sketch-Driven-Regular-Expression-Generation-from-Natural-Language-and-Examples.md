---
layout: post
title: "Sketch-Driven Regular Expression Generation from Natural Language and Examples"
date: 2019-08-16 05:09:57
categories: arXiv_CL
tags: arXiv_CL
author: Xi Ye, Qiaochu Chen, Xinyu Wang, Isil Dillig, Greg Durrett
mathjax: true
---

* content
{:toc}

##### Abstract
Recent systems for converting natural language descriptions into regular expressions have achieved some success, but typically deal with short, formulaic text and can only produce simple regular expressions, limiting their applicability. Real-world regular expressions are complex, hard to describe with brief sentences, and sometimes require examples to fully convey the user's intent. We present a framework for regular expression synthesis in this setting where both natural language and examples are available. First, a semantic parser (either grammar-based or neural) maps the natural language description into an intermediate sketch, which is an incomplete regular expression containing holes to denote missing components. Then a program synthesizer enumerates the regular expression space defined by the sketch and finds a regular expression that is consistent with the given string examples. Our semantic parser can be trained from supervised or heuristically-derived sketches and additionally fine-tuned with weak supervision based on correctness of the synthesized regex. We conduct experiments on two public large-scale datasets (Kushman and Barzilay, 2013; Locascio et al., 2016) and a real-world dataset we collected from StackOverflow. Our system achieves state-of-the-art performance on the public datasets and successfully solves 57% of the real-world dataset, which existing neural systems completely fail on.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05848](https://arxiv.org/abs/1908.05848)

##### PDF
[https://arxiv.org/pdf/1908.05848](https://arxiv.org/pdf/1908.05848)

