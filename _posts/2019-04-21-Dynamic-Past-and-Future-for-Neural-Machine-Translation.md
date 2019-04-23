---
layout: post
title: "Dynamic Past and Future for Neural Machine Translation"
date: 2019-04-21 19:07:07
categories: arXiv_CL
tags: arXiv_CL NMT
author: Zaixiang Zheng, Shujian Huang, Zhaopeng Tu, Xin-Yu Dai, Jiajun Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Previous studies have shown that neural machine translation (NMT) models can benefit from modeling translated (Past) and un-translated (Future) source contents as recurrent states (Zheng et al., 2018). However, the recurrent process is less interpretable. In this paper, we propose to model Past and Future by Capsule Network (Hinton et al.,2011), which provides an explicit separation of source words into groups of Past and Future by the process of parts-to-wholes assignment. The assignment is learned with a novel variant of routing-by-agreement mechanism (Sabour et al., 2017), namely Guided Dynamic Routing, in which what to translate at current decoding step guides the routing process to assign each source word to its associated group represented by a capsule, and to refine the representation of the capsule dynamically and iteratively. Experiments on translation tasks of three language pairs show that our model achieves substantial improvements over both RNMT and Transformer. Extensive analysis further verifies that our method does recognize translated and untranslated content as expected, and produces better and more adequate translations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09646](http://arxiv.org/abs/1904.09646)

##### PDF
[http://arxiv.org/pdf/1904.09646](http://arxiv.org/pdf/1904.09646)

