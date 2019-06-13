---
layout: post
title: "Weakly-supervised Compositional FeatureAggregation for Few-shot Recognition"
date: 2019-06-11 21:34:09
categories: arXiv_CV
tags: arXiv_CV Regularization Action_Recognition Image_Classification Optimization Classification Recognition
author: Ping Hu, Ximeng Sun, Kate Saenko, Stan Sclaroff
mathjax: true
---

* content
{:toc}

##### Abstract
Learning from a few examples is a challenging task for machine learning. While recent progress has been made for this problem, most of the existing methods ignore the compositionality in visual concept representation (e.g. objects are built from parts or composed of semantic attributes), which is key to the human ability to easily learn from a small number of examples. To enhance the few-shot learning models with compositionality, in this paper we present the simple yet powerful Compositional Feature Aggregation (CFA) module as a weakly-supervised regularization for deep networks. Given the deep feature maps extracted from the input, our CFA module first disentangles the feature space into disjoint semantic subspaces that model different attributes, and then bilinearly aggregates the local features within each of these subspaces. CFA explicitly regularizes the representation with both semantic and spatial compositionality to produce discriminative representations for few-shot recognition tasks. Moreover, our method does not need any supervision for attributes and object parts during training, thus can be conveniently plugged into existing models for end-to-end optimization while keeping the model size and computation cost nearly the same. Extensive experiments on few-shot image classification and action recognition tasks demonstrate that our method provides substantial improvements over recent state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04833](http://arxiv.org/abs/1906.04833)

##### PDF
[http://arxiv.org/pdf/1906.04833](http://arxiv.org/pdf/1906.04833)

