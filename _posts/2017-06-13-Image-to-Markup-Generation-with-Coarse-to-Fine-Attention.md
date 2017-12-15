---
layout: post
title: "Image-to-Markup Generation with Coarse-to-Fine Attention"
date: 2017-06-13 22:48:53
categories: arXiv_CL
tags: arXiv_CL OCR Attention Inference
author: Yuntian Deng, Anssi Kanervisto, Jeffrey Ling, Alexander M. Rush
mathjax: true
---

* content
{:toc}

##### Abstract
We present a neural encoder-decoder model to convert images into presentational markup based on a scalable coarse-to-fine attention mechanism. Our method is evaluated in the context of image-to-LaTeX generation, and we introduce a new dataset of real-world rendered mathematical expressions paired with LaTeX markup. We show that unlike neural OCR techniques using CTC-based models, attention-based approaches can tackle this non-standard OCR task. Our approach outperforms classical mathematical OCR systems by a large margin on in-domain rendered data, and, with pretraining, also performs well on out-of-domain handwritten data. To reduce the inference complexity associated with the attention-based approaches, we introduce a new coarse-to-fine attention layer that selects a support region before applying attention.

##### Abstract (translated by Google)
我们提出了一个神经编码器 - 解码器模型来将图像转换为基于可扩展的从粗到细的关注机制的表示标记。我们的方法是在图像到LaTeX世代的背景下进行评估的，我们引入了一个新的与LaTeX标记配对的现实世界的数学表达式。我们表明，不同于使用基于CTC的模型的神经OCR技术，基于注意的方法可以解决这个非标准的OCR任务。我们的方法比经典的数学OCR系统在区域内渲染的数据上大大优于传统的数学OCR系统，而且通过预训练，也可以很好地处理域外手写数据。为了减少与基于注意的方法相关的推理复杂性，我们引入了一个新的从粗到细的注意层，在应用注意力之前选择一个支持区域。

##### URL
[https://arxiv.org/abs/1609.04938](https://arxiv.org/abs/1609.04938)

##### PDF
[https://arxiv.org/pdf/1609.04938](https://arxiv.org/pdf/1609.04938)

