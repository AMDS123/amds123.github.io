---
layout: post
title: "A Neural Virtual Anchor Synthesizer based on Seq2Seq and GAN Models"
date: 2019-08-20 10:27:31
categories: arXiv_CV
tags: arXiv_CV GAN Face Embedding Language_Model
author: Zipeng Wang, Zhaoxiang Liu, Zezhou Chen, Huan Hu, Shiguo Lian
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel framework to generate realistic face video of an anchor, who is reading certain news. This task is also known as Virtual Anchor. Given some paragraphs of words, we first utilize a pretrained Word2Vec model to embed each word into a vector; then we utilize a Seq2Seq-based model to translate these word embeddings into action units and head poses of the target anchor; these action units and head poses will be concatenated with facial landmarks as well as the former $n$ synthesized frames, and the concatenation serves as input of a Pix2PixHD-based model to synthesize realistic facial images for the virtual anchor. The experimental results demonstrate our framework is feasible for the synthesis of virtual anchor.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07262](http://arxiv.org/abs/1908.07262)

##### PDF
[http://arxiv.org/pdf/1908.07262](http://arxiv.org/pdf/1908.07262)

