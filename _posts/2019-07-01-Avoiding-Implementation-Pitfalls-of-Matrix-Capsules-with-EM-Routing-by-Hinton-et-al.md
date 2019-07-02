---
layout: post
title: "Avoiding Implementation Pitfalls of 'Matrix Capsules with EM Routing' by Hinton et al"
date: 2019-07-01 10:51:58
categories: arXiv_AI
tags: arXiv_AI GAN
author: Ashley Daniel Gritzman
mathjax: true
---

* content
{:toc}

##### Abstract
The recent progress on capsule networks by Hinton et al. has generated considerable excitement in the machine learning community. The idea behind a capsule is inspired by a cortical minicolumn in the brain, whereby a vertically organised group of around 100 neurons receive common inputs, have common outputs, are interconnected, and may well constitute a fundamental computation unit of the cerebral cortex. However, Hinton's paper on "Matrix Capsule with EM Routing'" was unfortunately not accompanied by a release of source code, which left interested researchers attempting to implement the architecture and reproduce the benchmarks on their own. This has certainly slowed the progress of research building on this work. While writing our own implementation, we noticed several common mistakes in other open source implementations that we came across. In this paper we share some of these learnings, specifically focusing on three implementation pitfalls and how to avoid them: (1) parent capsules with only one child; (2) normalising the amount of data assigned to parent capsules; (3) parent capsules at different positions compete for child capsules. While our implementation is a considerable improvement over currently available implementations, it still falls slightly short of the performance reported by Hinton et al. (2018). The source code for this implementation is available on GitHub at the following URL: https://github.com/IBM/matrix-capsules-with-em-routing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00652](http://arxiv.org/abs/1907.00652)

##### PDF
[http://arxiv.org/pdf/1907.00652](http://arxiv.org/pdf/1907.00652)

