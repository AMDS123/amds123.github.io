---
layout: post
title: "Transcribing Content from Structural Images with Spotlight Mechanism"
date: 2019-05-27 03:25:29
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Yu Yin, Zhenya Huang, Enhong Chen, Qi Liu, Fuzheng Zhang, Xing Xie, Guoping Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Transcribing content from structural images, e.g., writing notes from music scores, is a challenging task as not only the content objects should be recognized, but the internal structure should also be preserved. Existing image recognition methods mainly work on images with simple content (e.g., text lines with characters), but are not capable to identify ones with more complex content (e.g., structured symbols), which often follow a fine-grained grammar. To this end, in this paper, we propose a hierarchical Spotlight Transcribing Network (STN) framework followed by a two-stage "where-to-what" solution. Specifically, we first decide "where-to-look" through a novel spotlight mechanism to focus on different areas of the original image following its structure. Then, we decide "what-to-write" by developing a GRU based network with the spotlight areas for transcribing the content accordingly. Moreover, we propose two implementations on the basis of STN, i.e., STNM and STNR, where the spotlight movement follows the Markov property and Recurrent modeling, respectively. We also design a reinforcement method to refine the framework by self-improving the spotlight mechanism. We conduct extensive experiments on many structural image datasets, where the results clearly demonstrate the effectiveness of STN framework.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10954](http://arxiv.org/abs/1905.10954)

##### PDF
[http://arxiv.org/pdf/1905.10954](http://arxiv.org/pdf/1905.10954)

