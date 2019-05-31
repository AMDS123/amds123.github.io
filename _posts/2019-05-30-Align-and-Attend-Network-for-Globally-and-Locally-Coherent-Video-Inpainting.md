---
layout: post
title: "Align-and-Attend Network for Globally and Locally Coherent Video Inpainting"
date: 2019-05-30 14:14:08
categories: arXiv_CV
tags: arXiv_CV Attention Relation
author: Sanghyun Woo, Dahun Kim, KwanYong Park, Joon-Young Lee, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel feed-forward network for video inpainting. We use a set of sampled video frames as the reference to take visible contents to fill the hole of a target frame. Our video inpainting network consists of two stages. The first stage is an alignment module that uses computed homographies between the reference frames and the target frame. The visible patches are then aggregated based on the frame similarity to fill in the target holes roughly. The second stage is a non-local attention module that matches the generated patches with known reference patches (in space and time) to refine the previous global alignment stage. Both stages consist of large spatial-temporal window size for the reference and thus enable modeling long-range correlations between distant information and the hole regions. Therefore, even challenging scenes with large or slowly moving holes can be handled, which have been hardly modeled by existing flow-based approach. Our network is also designed with a recurrent propagation stream to encourage temporal consistency in video results. Experiments on video object removal demonstrate that our method inpaints the holes with globally and locally coherent contents.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13066](http://arxiv.org/abs/1905.13066)

##### PDF
[http://arxiv.org/pdf/1905.13066](http://arxiv.org/pdf/1905.13066)

