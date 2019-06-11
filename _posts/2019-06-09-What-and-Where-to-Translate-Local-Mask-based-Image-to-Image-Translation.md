---
layout: post
title: "What and Where to Translate: Local Mask-based Image-to-Image Translation"
date: 2019-06-09 09:07:01
categories: arXiv_CV
tags: arXiv_CV Attention Quantitative
author: Wonwoong Cho, Seunghwan Choi, Junwoo Park, David Keetae Park, Tao Qin, Jaegul Choo
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, image-to-image translation has obtained significant attention. Among many, those approaches based on an exemplar image that contains the target style information has been actively studied, due to its capability to handle multimodality as well as its applicability in practical use. However, two intrinsic problems exist in the existing methods: what and where to transfer. First, those methods extract style from an entire exemplar which includes noisy information, which impedes a translation model from properly extracting the intended style of the exemplar. That is, we need to carefully determine what to transfer from the exemplar. Second, the extracted style is applied to the entire input image, which causes unnecessary distortion in irrelevant image regions. In response, we need to decide where to transfer the extracted style. In this paper, we propose a novel approach that extracts out a local mask from the exemplar that determines what style to transfer, and another local mask from the input image that determines where to transfer the extracted style. The main novelty of this paper lies in (1) the highway adaptive instance normalization technique and (2) an end-to-end translation framework which achieves an outstanding performance in reflecting a style of an exemplar. We demonstrate the quantitative and qualitative evaluation results to confirm the advantages of our proposed approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03598](http://arxiv.org/abs/1906.03598)

##### PDF
[http://arxiv.org/pdf/1906.03598](http://arxiv.org/pdf/1906.03598)

