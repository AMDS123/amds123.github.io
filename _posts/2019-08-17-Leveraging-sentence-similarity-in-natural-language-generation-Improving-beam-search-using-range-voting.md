---
layout: post
title: "Leveraging sentence similarity in natural language generation: Improving beam search using range voting"
date: 2019-08-17 10:36:43
categories: arXiv_CL
tags: arXiv_CL Image_Caption Caption Language_Model
author: Sebastian Borgeaud, Guy Emerson
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for generating natural language sentences from probabilistic language models, selecting from a beam search using a range voting procedure. The proposed method could be applied to any language model, including both n-gram models and neural network models, and could be applied to any generation task. Instead of choosing the most likely output, our method chooses the most representative output, providing a solution to the common problem of short outputs being preferred over longer and more informative ones. We evaluate our method on an image captioning task, and find that the generated captions are longer and more diverse than those generated using standard beam search, with higher BLEU scores (particularly when the beam size is large), and better performance in a human evaluation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06288](http://arxiv.org/abs/1908.06288)

##### PDF
[http://arxiv.org/pdf/1908.06288](http://arxiv.org/pdf/1908.06288)

