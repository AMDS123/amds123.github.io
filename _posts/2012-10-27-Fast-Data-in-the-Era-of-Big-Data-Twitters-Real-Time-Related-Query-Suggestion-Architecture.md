---
layout: post
title: "Fast Data in the Era of Big Data: Twitter's Real-Time Related Query Suggestion Architecture"
date: 2012-10-27 17:20:42
categories: arXiv_CV
tags: arXiv_CV Attention
author: Gilad Mishne, Jeff Dalton, Zhenghua Li, Aneesh Sharma, Jimmy Lin
mathjax: true
---

* content
{:toc}

##### Abstract
We present the architecture behind Twitter's real-time related query suggestion and spelling correction service. Although these tasks have received much attention in the web search literature, the Twitter context introduces a real-time "twist": after significant breaking news events, we aim to provide relevant results within minutes. This paper provides a case study illustrating the challenges of real-time data processing in the era of "big data". We tell the story of how our system was built twice: our first implementation was built on a typical Hadoop-based analytics stack, but was later replaced because it did not meet the latency requirements necessary to generate meaningful real-time results. The second implementation, which is the system deployed in production, is a custom in-memory processing engine specifically designed for the task. This experience taught us that the current typical usage of Hadoop as a "big data" platform, while great for experimentation, is not well suited to low-latency processing, and points the way to future work on data analytics platforms that can handle "big" as well as "fast" data.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1210.7350](https://arxiv.org/abs/1210.7350)

##### PDF
[https://arxiv.org/pdf/1210.7350](https://arxiv.org/pdf/1210.7350)

