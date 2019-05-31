---
layout: post
title: "Multi-level Multimodal Common Semantic Space for Image-Phrase Grounding"
date: 2019-05-29 20:49:53
categories: arXiv_CV
tags: arXiv_CV Attention Embedding CNN Language_Model
author: Hassan Akbari, Svebor Karaman, Surabhi Bhargava, Brian Chen, Carl Vondrick, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of phrase grounding by lear ing a multi-level common semantic space shared by the textual and visual modalities. We exploit multiple levels of feature maps of a Deep Convolutional Neural Network, as well as contextualized word and sentence embeddings extracted from a character-based language model. Following dedicated non-linear mappings for visual features at each level, word, and sentence embeddings, we obtain multiple instantiations of our common semantic space in which comparisons between any target text and the visual content is performed with cosine similarity. We guide the model by a multi-level multimodal attention mechanism which outputs attended visual features at each level. The best level is chosen to be compared with text content for maximizing the pertinence scores of image-sentence pairs of the ground truth. Experiments conducted on three publicly available datasets show significant performance gains (20%-60% relative) over the state-of-the-art in phrase localization and set a new performance record on those datasets. We provide a detailed ablation study to show the contribution of each element of our approach and release our code on GitHub.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11683](http://arxiv.org/abs/1811.11683)

##### PDF
[http://arxiv.org/pdf/1811.11683](http://arxiv.org/pdf/1811.11683)

