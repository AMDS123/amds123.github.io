---
layout: post
title: "Enabling Multi-Source Neural Machine Translation By Concatenating Source Sentences In Multiple Languages"
date: 2019-03-04 04:10:10
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Raj Dabre, Fabien Cromieres, Sadao Kurohashi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we explore a simple solution to "Multi-Source Neural Machine Translation" (MSNMT) which only relies on preprocessing a N-way multilingual corpus without modifying the Neural Machine Translation (NMT) architecture or training procedure. We simply concatenate the source sentences to form a single long multi-source input sentence while keeping the target side sentence as it is and train an NMT system using this preprocessed corpus. We evaluate our method in resource poor as well as resource rich settings and show its effectiveness (up to 4 BLEU using 2 source languages and up to 6 BLEU using 5 source languages). We also compare against existing methods for MSNMT and show that our solution gives competitive results despite its simplicity. We also provide some insights on how the NMT system leverages multilingual information in such a scenario by visualizing attention.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1702.06135](http://arxiv.org/abs/1702.06135)

##### PDF
[http://arxiv.org/pdf/1702.06135](http://arxiv.org/pdf/1702.06135)

