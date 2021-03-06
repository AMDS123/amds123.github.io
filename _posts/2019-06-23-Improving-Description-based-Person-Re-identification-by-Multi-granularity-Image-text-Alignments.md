---
layout: post
title: "Improving Description-based Person Re-identification by Multi-granularity Image-text Alignments"
date: 2019-06-23 17:06:45
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Relation
author: Kai Niu, Yan Huang, Wanli Ouyang, Liang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Description-based person re-identification (Re-id) is an important task in video surveillance that requires discriminative cross-modal representations to distinguish different people. It is difficult to directly measure the similarity between images and descriptions due to the modality heterogeneity (the cross-modal problem). And all samples belonging to a single category (the fine-grained problem) makes this task even harder than the conventional image-description matching task. In this paper, we propose a Multi-granularity Image-text Alignments (MIA) model to alleviate the cross-modal fine-grained problem for better similarity evaluation in description-based person Re-id. Specifically, three different granularities, i.e., global-global, global-local and local-local alignments are carried out hierarchically. Firstly, the global-global alignment in the Global Contrast (GC) module is for matching the global contexts of images and descriptions. Secondly, the global-local alignment employs the potential relations between local components and global contexts to highlight the distinguishable components while eliminating the uninvolved ones adaptively in the Relation-guided Global-local Alignment (RGA) module. Thirdly, as for the local-local alignment, we match visual human parts with noun phrases in the Bi-directional Fine-grained Matching (BFM) module. The whole network combining multiple granularities can be end-to-end trained without complex pre-processing. To address the difficulties in training the combination of multiple granularities, an effective step training strategy is proposed to train these granularities step-by-step. Extensive experiments and analysis have shown that our method obtains the state-of-the-art performance on the CUHK-PEDES dataset and outperforms the previous methods by a significant margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09610](http://arxiv.org/abs/1906.09610)

##### PDF
[http://arxiv.org/pdf/1906.09610](http://arxiv.org/pdf/1906.09610)

