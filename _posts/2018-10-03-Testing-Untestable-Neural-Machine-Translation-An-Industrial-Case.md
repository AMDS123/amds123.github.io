---
layout: post
title: "Testing Untestable Neural Machine Translation: An Industrial Case"
date: 2018-10-03 15:42:51
categories: arXiv_CL
tags: arXiv_CL NMT
author: Wujie Zheng, Wenyu Wang, Dian Liu, Changrong Zhang, Qinsong Zeng, Yuetang Deng, Wei Yang, Pinjia He, Tao Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) has been widely adopted recently due to its advantages compared with the traditional Statistical Machine Translation (SMT). However, an NMT system still often produces translation failures due to the complexity of natural language and sophistication in designing neural networks. While in-house black-box system testing based on reference translations (i.e., examples of valid translations) has been a common practice for NMT quality assurance, an increasingly critical industrial practice, named in-vivo testing, exposes unseen types or instances of translation failures when real users are using a deployed industrial NMT system. To fill the gap of lacking test oracle for in-vivo testing of an NMT system, in this paper, we propose a new approach for automatically identifying translation failures, without requiring reference translations for a translation task; our approach can directly serve as a test oracle for in-vivo testing. Our approach focuses on properties of natural language translation that can be checked systematically and uses information from both the test inputs (i.e., the texts to be translated) and the test outputs (i.e., the translations under inspection) of the NMT system. Our evaluation conducted on real-world datasets shows that our approach can effectively detect targeted property violations as translation failures. Our experiences on deploying our approach in both production and development environments of WeChat (a messenger app with over one billion monthly active users) demonstrate high effectiveness of our approach along with high industry impact.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.02340](https://arxiv.org/abs/1807.02340)

##### PDF
[https://arxiv.org/pdf/1807.02340](https://arxiv.org/pdf/1807.02340)

