---
layout: post
title: "Measuring scheduling efficiency of RNNs for NLP applications"
date: 2019-04-05 22:03:14
categories: arXiv_CV
tags: arXiv_CV Image_Caption Speech_Recognition Caption Optimization Inference RNN Recognition
author: Urmish Thakker, Ganesh Dasika, Jesse Beu, Matthew Mattina
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) have shown state of the art results for speech recognition, natural language processing, image captioning and video summarizing applications. Many of these applications run on low-power platforms, so their energy efficiency is extremely important. We observed that cache-oblivious RNN scheduling during inference typically results in 30-50x more data transferred on and off the CPU than the application's working set size. This can potentially impact its energy efficiency. This paper presents a new metric called Data Reuse Efficiency to gauge the RNN scheduling efficiency of a platform and shows the factors that influence the DRE value. Additionally, this paper discusses an optimization to improve reuse in RNNs and highlights the positive impact of this optimization on the total amount of memory read from or written to the memory controller (and, hence, the DRE value) during the execution of an RNN application for a mobile SoC.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.03302](https://arxiv.org/abs/1904.03302)

##### PDF
[https://arxiv.org/pdf/1904.03302](https://arxiv.org/pdf/1904.03302)

