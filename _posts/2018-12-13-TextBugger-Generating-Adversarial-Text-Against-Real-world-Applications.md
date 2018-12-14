---
layout: post
title: "TextBugger: Generating Adversarial Text Against Real-world Applications"
date: 2018-12-13 05:32:43
categories: arXiv_CL
tags: arXiv_CL Sentiment Adversarial Text_Classification Classification Deep_Learning Detection
author: Jinfeng Li, Shouling Ji, Tianyu Du, Bo Li, Ting Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Learning-based Text Understanding (DLTU) is the backbone technique behind various applications, including question answering, machine translation, and text classification. Despite its tremendous popularity, the security vulnerabilities of DLTU are still largely unknown, which is highly concerning given its increasing use in security-sensitive applications such as sentiment analysis and toxic content detection. In this paper, we show that DLTU is inherently vulnerable to adversarial text attacks, in which maliciously crafted texts trigger target DLTU systems and services to misbehave. Specifically, we present TextBugger, a general attack framework for generating adversarial texts. In contrast to prior works, TextBugger differs in significant ways: (i) effective -- it outperforms state-of-the-art attacks in terms of attack success rate; (ii) evasive -- it preserves the utility of benign text, with 94.9\% of the adversarial text correctly recognized by human readers; and (iii) efficient -- it generates adversarial text with computational complexity sub-linear to the text length. We empirically evaluate TextBugger on a set of real-world DLTU systems and services used for sentiment analysis and toxic content detection, demonstrating its effectiveness, evasiveness, and efficiency. For instance, TextBugger achieves 100\% success rate on the IMDB dataset based on Amazon AWS Comprehend within 4.61 seconds and preserves 97\% semantic similarity. We further discuss possible defense mechanisms to mitigate such attack and the adversary's potential countermeasures, which leads to promising directions for further research.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05271](http://arxiv.org/abs/1812.05271)

##### PDF
[http://arxiv.org/pdf/1812.05271](http://arxiv.org/pdf/1812.05271)

