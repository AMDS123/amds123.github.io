---
layout: post
title: "Generating Sentiment-Preserving Fake Online Reviews Using Neural Language Models and Their Human- and Machine-based Detection"
date: 2019-07-22 08:22:08
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Language_Model Detection
author: David Ifeoluwa Adelani, Haotian Mai, Fuming Fang, Huy H. Nguyen, Junichi Yamagishi, Isao Echizen
mathjax: true
---

* content
{:toc}

##### Abstract
Advanced neural language models (NLMs) are widely used in sequence generation tasks because they are able to produce fluent and meaningful sentences. They can also be used to generate fake reviews, which can then be used to attack online review systems and influence the buying decisions of online shoppers. A problem in fake review generation is how to generate the desired sentiment/topic. Existing solutions first generate an initial review based on some keywords and then modify some of the words in the initial review so that the review has the desired sentiment/topic. We overcome this problem by using the GPT-2 NLM to generate a large number of high-quality reviews based on a review with the desired sentiment and then using a BERT based text classifier (with accuracy of 96\%) to filter out reviews with undesired sentiments. Because none of the words in the review are modified, fluent samples like the training data can be generated from the learned distribution. A subjective evaluation with 80 participants demonstrated that this simple method can produce reviews that are as fluent as those written by people. It also showed that the participants tended to distinguish fake reviews randomly. Two countermeasures, GROVER and GLTR, were found to be able to accurately detect fake review.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09177](http://arxiv.org/abs/1907.09177)

##### PDF
[http://arxiv.org/pdf/1907.09177](http://arxiv.org/pdf/1907.09177)

