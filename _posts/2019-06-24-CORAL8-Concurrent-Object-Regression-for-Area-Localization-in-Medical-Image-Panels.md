---
layout: post
title: "CORAL8: Concurrent Object Regression for Area Localization in Medical Image Panels"
date: 2019-06-24 00:30:32
categories: arXiv_AI
tags: arXiv_AI Regularization Attention RNN
author: Sam Maksoud, Arnold Wiliem, Kun Zhao, Teng Zhang, Lin Wu, Brian C. Lovell
mathjax: true
---

* content
{:toc}

##### Abstract
This work tackles the problem of generating a medical report for multi-image panels. We apply our solution to the Renal Direct Immunofluorescence (RDIF) assay which requires a pathologist to generate a report based on observations across the eight different WSI in concert with existing clinical features. To this end, we propose a novel attention-based multi-modal generative recurrent neural network (RNN) architecture capable of dynamically sampling image data concurrently across the RDIF panel. The proposed methodology incorporates text from the clinical notes of the requesting physician to regulate the output of the network to align with the overall clinical context. In addition, we found the importance of regularizing the attention weights for word generation processes. This is because the system can ignore the attention mechanism by assigning equal weights for all members. Thus, we propose two regularizations which force the system to utilize the attention mechanism. Experiments on our novel collection of RDIF WSIs provided by a large clinical laboratory demonstrate that our framework offers significant improvements over existing methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09676](http://arxiv.org/abs/1906.09676)

##### PDF
[http://arxiv.org/pdf/1906.09676](http://arxiv.org/pdf/1906.09676)

