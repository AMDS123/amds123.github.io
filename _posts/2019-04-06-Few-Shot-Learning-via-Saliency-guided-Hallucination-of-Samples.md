---
layout: post
title: "Few-Shot Learning via Saliency-guided Hallucination of Samples"
date: 2019-04-06 15:33:39
categories: arXiv_CV
tags: arXiv_CV Salient Knowledge GAN
author: Hongguang Zhang, Jing Zhang, Piotr Koniusz
mathjax: true
---

* content
{:toc}

##### Abstract
Learning new concepts from a few of samples is a standard challenge in computer vision. The main directions to improve the learning ability of few-shot training models include (i) a robust similarity learning and (ii) generating or hallucinating additional data from the limited existing samples. In this paper, we follow the latter direction and present a novel data hallucination model. Currently, most datapoint generators contain a specialized network (i.e., GAN) tasked with hallucinating new datapoints, thus requiring large numbers of annotated data for their training in the first place. In this paper, we propose a novel less-costly hallucination method for few-shot learning which utilizes saliency maps. To this end, we employ a saliency network to obtain the foregrounds and backgrounds of available image samples and feed the resulting maps into a two-stream network to hallucinate datapoints directly in the feature space from viable foreground-background combinations. To the best of our knowledge, we are the first to leverage saliency maps for such a task and we demonstrate their usefulness in hallucinating additional datapoints for few-shot learning. Our proposed network achieves the state of the art on publicly available datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03472](http://arxiv.org/abs/1904.03472)

##### PDF
[http://arxiv.org/pdf/1904.03472](http://arxiv.org/pdf/1904.03472)

