---
layout: post
title: "Compact Tensor Pooling for Visual Question Answering"
date: 2017-06-20 23:55:32
categories: arXiv_CV
tags: arXiv_CV QA Embedding RNN VQA
author: Yang Shi, Tommaso Furlanello, Anima Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Performing high level cognitive tasks requires the integration of feature maps with drastically different structure. In Visual Question Answering (VQA) image descriptors have spatial structures, while lexical inputs inherently follow a temporal sequence. The recently proposed Multimodal Compact Bilinear pooling (MCB) forms the outer products, via count-sketch approximation, of the visual and textual representation at each spatial location. While this procedure preserves spatial information locally, outer-products are taken independently for each fiber of the activation tensor, and therefore do not include spatial context. In this work, we introduce multi-dimensional sketch ({MD-sketch}), a novel extension of count-sketch to tensors. Using this new formulation, we propose Multimodal Compact Tensor Pooling (MCT) to fully exploit the global spatial context during bilinear pooling operations. Contrarily to MCB, our approach preserves spatial context by directly convolving the MD-sketch from the visual tensor features with the text vector feature using higher order FFT. Furthermore we apply MCT incrementally at each step of the question embedding and accumulate the multi-modal vectors with a second LSTM layer before the final answer is chosen.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.06706](https://arxiv.org/abs/1706.06706)

##### PDF
[https://arxiv.org/pdf/1706.06706](https://arxiv.org/pdf/1706.06706)

