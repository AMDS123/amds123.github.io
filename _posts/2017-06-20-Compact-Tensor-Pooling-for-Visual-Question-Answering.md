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
执行高级认知任务需要集成具有截然不同结构的特征映射。在视觉问题回答（VQA）中，图像描述符具有空间结构，而词汇输入固有地遵循时间序列。最近提出的Multimodal Compact Bilinear pooling（MCB）通过计数草图近似形成了每个空间位置的视觉和文本表示的外部产品。虽然该过程在本地保留空间信息，但是对于激活张量的每个光纤独立地采用外积，因此不包括空间上下文。在这项工作中，我们介绍了多维草图（{MD-sketch}），这是计数草图到张量的新颖扩展。使用这个新的公式，我们提出多模态紧凑张量池（MCT），以充分利用双线性池操作期间的全球空间背景。与MCB相反，我们的方法通过使用更高阶FFT直接将视觉张量特征的MD草图与文本向量特征卷积来保留空间背景。此外，我们在问题嵌入的每个步骤递增地应用MCT，并在选择最终答案之前用第二个LSTM层累积多模态向量。

##### URL
[https://arxiv.org/abs/1706.06706](https://arxiv.org/abs/1706.06706)

##### PDF
[https://arxiv.org/pdf/1706.06706](https://arxiv.org/pdf/1706.06706)

