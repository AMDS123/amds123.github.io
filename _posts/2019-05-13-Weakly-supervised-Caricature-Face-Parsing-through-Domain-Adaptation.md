---
layout: post
title: "Weakly-supervised Caricature Face Parsing through Domain Adaptation"
date: 2019-05-13 15:36:41
categories: arXiv_CV
tags: arXiv_CV Face Style_Transfer Recognition
author: Wenqing Chu, Wei-Chih Hung, Yi-Hsuan Tsai, Deng Cai, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
A caricature is an artistic form of a person's picture in which certain striking characteristics are abstracted or exaggerated in order to create a humor or sarcasm effect. For numerous caricature related applications such as attribute recognition and caricature editing, face parsing is an essential pre-processing step that provides a complete facial structure understanding. However, current state-of-the-art face parsing methods require large amounts of labeled data on the pixel-level and such process for caricature is tedious and labor-intensive. For real photos, there are numerous labeled datasets for face parsing. Thus, we formulate caricature face parsing as a domain adaptation problem, where real photos play the role of the source domain, adapting to the target caricatures. Specifically, we first leverage a spatial transformer based network to enable shape domain shifts. A feed-forward style transfer network is then utilized to capture texture-level domain gaps. With these two steps, we synthesize face caricatures from real photos, and thus we can use parsing ground truths of the original photos to learn the parsing model. Experimental results on the synthetic and real caricatures demonstrate the effectiveness of the proposed domain adaptation algorithm. Code is available at: https://github.com/ZJULearning/CariFaceParsing .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.05091](http://arxiv.org/abs/1905.05091)

##### PDF
[http://arxiv.org/pdf/1905.05091](http://arxiv.org/pdf/1905.05091)

