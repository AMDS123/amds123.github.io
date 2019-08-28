---
layout: post
title: "Controllable Video Captioning with POS Sequence Guidance Based on Gated Fusion Network"
date: 2019-08-27 08:22:54
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption
author: Bairui Wang, Lin Ma, Wei Zhang, Wenhao Jiang, Jingwen Wang, Wei Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose to guide the video caption generation with Part-of-Speech (POS) information, based on a gated fusion of multiple representations of input videos. We construct a novel gated fusion network, with one particularly designed cross-gating (CG) block, to effectively encode and fuse different types of representations, e.g., the motion and content features of an input video. One POS sequence generator relies on this fused representation to predict the global syntactic structure, which is thereafter leveraged to guide the video captioning generation and control the syntax of the generated sentence. Specifically, a gating strategy is proposed to dynamically and adaptively incorporate the global syntactic POS information into the decoder for generating each word. Experimental results on two benchmark datasets, namely MSR-VTT and MSVD, demonstrate that the proposed model can well exploit complementary information from multiple representations, resulting in improved performances. Moreover, the generated global POS information can well capture the global syntactic structure of the sentence, and thus be exploited to control the syntactic structure of the description. Such POS information not only boosts the video captioning performance but also improves the diversity of the generated captions. Our code is at: https://github.com/vsislab/Controllable_XGating.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10072](http://arxiv.org/abs/1908.10072)

##### PDF
[http://arxiv.org/pdf/1908.10072](http://arxiv.org/pdf/1908.10072)

