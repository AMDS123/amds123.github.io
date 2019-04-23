---
layout: post
title: "The Curious Case of Neural Text Degeneration"
date: 2019-04-22 07:17:18
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Ari Holtzman, Jan Buys, Maxwell Forbes, Yejin Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Despite considerable advancements with deep neural language models, the enigma of neural text degeneration persists when these models are tested as text generators. The counter-intuitive empirical observation is that even though the use of likelihood as training objective leads to high quality models for a broad range of language understanding tasks, using likelihood as a decoding objective leads to text that is bland and strangely repetitive. 
 In this paper, we reveal surprising distributional differences between human text and machine text. In addition, we find that decoding strategies alone can dramatically effect the quality of machine text, even when generated from exactly the same neural language model. 
 Our findings motivate Nucleus Sampling, a simple but effective method to draw the best out of neural generation. By sampling text from the dynamic nucleus of the probability distribution, which allows for diversity while effectively truncating the less reliable tail of the distribution, the resulting text better demonstrates the quality of human text, yielding enhanced diversity without sacrificing fluency and coherence.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09751](http://arxiv.org/abs/1904.09751)

##### PDF
[http://arxiv.org/pdf/1904.09751](http://arxiv.org/pdf/1904.09751)

