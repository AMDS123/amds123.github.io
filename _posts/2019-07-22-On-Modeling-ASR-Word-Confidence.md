---
layout: post
title: "On Modeling ASR Word Confidence"
date: 2019-07-22 23:53:41
categories: arXiv_CL
tags: arXiv_CL
author: Woojay Jeon, Maxwell Jordan, Mahesh Krishnamoorthy
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new method for computing ASR word confidences that effectively mitigates ASR errors for diverse downstream applications, improves the word error rate of the 1-best result, and allows better comparison of scores across different models. We propose 1) a new method for modeling word confidence using a Heterogeneous Word Confusion Network (HWCN) that addresses some key flaws in conventional Word Confusion Networks, and 2) a new score calibration method for facilitating direct comparison of scores from different models. Using a bidirectional lattice recurrent neural network to compute the confidence scores of each word in the HWCN, we show that the word sequence with the best overall confidence is more accurate than the default 1-best result of the recognizer, and that the calibration method greatly improves the reliability of recognizer combination.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09636](http://arxiv.org/abs/1907.09636)

##### PDF
[http://arxiv.org/pdf/1907.09636](http://arxiv.org/pdf/1907.09636)

