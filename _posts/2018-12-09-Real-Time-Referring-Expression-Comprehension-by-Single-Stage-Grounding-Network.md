---
layout: post
title: "Real-Time Referring Expression Comprehension by Single-Stage Grounding Network"
date: 2018-12-09 04:30:11
categories: arXiv_CV
tags: arXiv_CV Attention
author: Xinpeng Chen, Lin Ma, Jingyuan Chen, Zequn Jie, Wei Liu, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel end-to-end model, namely Single-Stage Grounding network (SSG), to localize the referent given a referring expression within an image. Different from previous multi-stage models which rely on object proposals or detected regions, our proposed model aims to comprehend a referring expression through one single stage without resorting to region proposals as well as the subsequent region-wise feature extraction. Specifically, a multimodal interactor is proposed to summarize the local region features regarding the referring expression attentively. Subsequently, a grounder is proposed to localize the referring expression within the given image directly. For further improving the localization accuracy, a guided attention mechanism is proposed to enforce the grounder to focus on the central region of the referent. Moreover, by exploiting and predicting visual attribute information, the grounder can further distinguish the referent objects within an image and thereby improve the model performance. Experiments on RefCOCO, RefCOCO+, and RefCOCOg datasets demonstrate that our proposed SSG without relying on any region proposals can achieve comparable performance with other advanced models. Furthermore, our SSG outperforms the previous models and achieves the state-of-art performance on the ReferItGame dataset. More importantly, our SSG is time efficient and can ground a referring expression in a 416*416 image from the RefCOCO dataset in 25ms (40 referents per second) on average with a Nvidia Tesla P40, accomplishing more than 9* speedups over the existing multi-stage models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03426](http://arxiv.org/abs/1812.03426)

##### PDF
[http://arxiv.org/pdf/1812.03426](http://arxiv.org/pdf/1812.03426)

