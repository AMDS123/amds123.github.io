---
layout: post
title: "Multi-level Multimodal Common Semantic Space for Image-Phrase Grounding"
date: 2018-11-28 17:05:27
categories: arXiv_CV
tags: arXiv_CV Attention Embedding CNN Language_Model
author: Hassan Akbari, Svebor Karaman, Surabhi Bhargava, Brian Chen, Carl Vondrick, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of phrase grounding by learning a multi-level common semantic space shared by the textual and visual modalities. This common space is instantiated at multiple layers of a Deep Convolutional Neural Network by exploiting its feature maps, as well as contextualized word-level and sentence-level embeddings extracted from a character-based language model. Following a dedicated non-linear mapping for visual features at each level, word, and sentence embeddings, we obtain a common space in which comparisons between the target text and the visual content at any semantic level can be performed simply with cosine similarity. We guide the model by a multi-level multimodal attention mechanism which outputs attended visual features at different semantic levels. The best level is chosen to be compared with text content for maximizing the pertinence scores of image-sentence pairs of the ground truth. Experiments conducted on three publicly available benchmarks show significant performance gains (20%-60% relative) over the state-of-the-art in phrase localization and set a new performance record on those datasets. We also provide a detailed ablation study to show the contribution of each element of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11683](http://arxiv.org/abs/1811.11683)

##### PDF
[http://arxiv.org/pdf/1811.11683](http://arxiv.org/pdf/1811.11683)

