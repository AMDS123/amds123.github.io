---
layout: post
title: "LXMERT: Learning Cross-Modality Encoder Representations from Transformers"
date: 2019-08-20 17:05:18
categories: arXiv_CV
tags: arXiv_CV QA Classification Language_Model Prediction Relation VQA
author: Hao Tan, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Vision-and-language reasoning requires an understanding of visual concepts, language semantics, and, most importantly, the alignment and relationships between these two modalities. We thus propose the LXMERT (Learning Cross-Modality Encoder Representations from Transformers) framework to learn these vision-and-language connections. In LXMERT, we build a large-scale Transformer model that consists of three encoders: an object relationship encoder, a language encoder, and a cross-modality encoder. Next, to endow our model with the capability of connecting vision and language semantics, we pre-train the model with large amounts of image-and-sentence pairs, via five diverse representative pre-training tasks: masked language modeling, masked object prediction (feature regression and label classification), cross-modality matching, and image question answering. These tasks help in learning both intra-modality and cross-modality relationships. After fine-tuning from our pre-trained parameters, our model achieves the state-of-the-art results on two visual question answering datasets (i.e., VQA and GQA). We also show the generalizability of our pre-trained cross-modality model by adapting it to a challenging visual-reasoning task, NLVR2, and improve the previous best result by 22% absolute (54% to 76%). Lastly, we demonstrate detailed ablation studies to prove that both our novel model components and pre-training strategies significantly contribute to our strong results. Code and pre-trained models publicly available at: https://github.com/airsplay/lxmert

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07490](http://arxiv.org/abs/1908.07490)

##### PDF
[http://arxiv.org/pdf/1908.07490](http://arxiv.org/pdf/1908.07490)

