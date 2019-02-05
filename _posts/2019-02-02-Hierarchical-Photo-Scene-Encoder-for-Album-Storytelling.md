---
layout: post
title: "Hierarchical Photo-Scene Encoder for Album Storytelling"
date: 2019-02-02 08:42:58
categories: arXiv_CV
tags: arXiv_CV Relation
author: Bairui Wang, Lin Ma, Wei Zhang, Wenhao Jiang, Feng Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel model with a hierarchical photo-scene encoder and a reconstructor for the task of album storytelling. The photo-scene encoder contains two sub-encoders, namely the photo and scene encoders, which are stacked together and behave hierarchically to fully exploit the structure information of the photos within an album. Specifically, the photo encoder generates semantic representation for each photo while exploiting temporal relationships among them. The scene encoder, relying on the obtained photo representations, is responsible for detecting the scene changes and generating scene representations. Subsequently, the decoder dynamically and attentively summarizes the encoded photo and scene representations to generate a sequence of album representations, based on which a story consisting of multiple coherent sentences is generated. In order to fully extract the useful semantic information from an album, a reconstructor is employed to reproduce the summarized album representations based on the hidden states of the decoder. The proposed model can be trained in an end-to-end manner, which results in an improved performance over the state-of-the-arts on the public visual storytelling (VIST) dataset. Ablation studies further demonstrate the effectiveness of the proposed hierarchical photo-scene encoder and reconstructor.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00669](http://arxiv.org/abs/1902.00669)

##### PDF
[http://arxiv.org/pdf/1902.00669](http://arxiv.org/pdf/1902.00669)

