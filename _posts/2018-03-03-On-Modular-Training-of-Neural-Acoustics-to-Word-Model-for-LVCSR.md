---
layout: post
title: "On Modular Training of Neural Acoustics-to-Word Model for LVCSR"
date: 2018-03-03 02:08:46
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Inference Language_Model Recognition
author: Zhehuai Chen, Qi Liu, Hao Li, Kai Yu
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end (E2E) automatic speech recognition (ASR) systems directly map acoustics to words using a unified model. Previous works mostly focus on E2E training a single model which integrates acoustic and language model into a whole. Although E2E training benefits from sequence modeling and simplified decoding pipelines, large amount of transcribed acoustic data is usually required, and traditional acoustic and language modelling techniques cannot be utilized. In this paper, a novel modular training framework of E2E ASR is proposed to separately train neural acoustic and language models during training stage, while still performing end-to-end inference in decoding stage. Here, an acoustics-to-phoneme model (A2P) and a phoneme-to-word model (P2W) are trained using acoustic data and text data respectively. A phone synchronous decoding (PSD) module is inserted between A2P and P2W to reduce sequence lengths without precision loss. Finally, modules are integrated into an acousticsto-word model (A2W) and jointly optimized using acoustic data to retain the advantage of sequence modeling. Experiments on a 300- hour Switchboard task show significant improvement over the direct A2W model. The efficiency in both training and decoding also benefits from the proposed method.

##### Abstract (translated by Google)
端到端（E2E）自动语音识别（ASR）系统使用统一模型将声学直接映射到单词。以前的工作主要集中在E2E培训一个单一的模型，将声学和语言模型整合到一起。虽然E2E训练受益于序列建模和简化的解码流水线，但通常需要大量的转录声学数据，而传统的声学和语言建模技术无法使用。本文提出了一种新颖的E2E ASR模块化训练框架，在训练阶段分别训练神经声学和语言模型，同时在解码阶段仍然进行端到端推理。在此，分别使用声学数据和文本数据来训练声学到音素模型（A2P）和音素到词模型（P2W）。在A2P和P2W之间插入电话同步解码（PSD）模块，以减少序列长度而不会造成精确损失。最后，将模块集成到声学模型（A2W）中，并使用声学数据进行联合优化以保留序列建模的优势。在300小时的交换机任务上的实验显示出比直接的A2W模型有显着的改进。在训练和解码中的效率也从所提出的方法中受益。

##### URL
[http://arxiv.org/abs/1803.01090](http://arxiv.org/abs/1803.01090)

##### PDF
[http://arxiv.org/pdf/1803.01090](http://arxiv.org/pdf/1803.01090)

