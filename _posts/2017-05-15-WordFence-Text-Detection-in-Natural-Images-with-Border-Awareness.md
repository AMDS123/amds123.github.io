---
layout: post
title: "WordFence: Text Detection in Natural Images with Border Awareness"
date: 2017-05-15 23:42:59
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Detection Recognition
author: Andrei Polzounov, Artsiom Ablavatski, Sergio Escalera, Shijian Lu, Jianfei Cai
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, text recognition has achieved remarkable success in recognizing scanned document text. However, word recognition in natural images is still an open problem, which generally requires time consuming post-processing steps. We present a novel architecture for individual word detection in scene images based on semantic segmentation. Our contributions are twofold: the concept of WordFence, which detects border areas surrounding each individual word and a novel pixelwise weighted softmax loss function which penalizes background and emphasizes small text regions. WordFence ensures that each word is detected individually, and the new loss function provides a strong training signal to both text and word border localization. The proposed technique avoids intensive post-processing, producing an end-to-end word detection system. We achieve superior localization recall on common benchmark datasets - 92% recall on ICDAR11 and ICDAR13 and 63% recall on SVT. Furthermore, our end-to-end word recognition system achieves state-of-the-art 86% F-Score on ICDAR13.

##### Abstract (translated by Google)
近年来，文本识别在识别扫描文档文本方面取得了显着的成功。然而，自然图像中的单词识别仍然是一个公开的问题，这通常需要耗时的后处理步骤。我们提出了一种基于语义分割的场景图像中单个词检测的新颖架构。我们的贡献是双重的：WordFence的概念，它检测每个单词周围的边界区域和一个新的像素加权的softmax损失函数惩罚背景和强调小文本区域。 WordFence确保每个单词被单独检测，而新的损失函数为文本和单词边界定位提供强大的训练信号。所提出的技术避免了密集的后处理，产生了端到端的字检测系统。我们在通用基准数据集上实现了卓越的本地化召回率--92％的ICDAR11和ICDAR13回收率和63％的SVT回收率。此外，我们的端到端单词识别系统在ICDAR13上实现了最先进的86％F-Score。

##### URL
[https://arxiv.org/abs/1705.05483](https://arxiv.org/abs/1705.05483)

##### PDF
[https://arxiv.org/pdf/1705.05483](https://arxiv.org/pdf/1705.05483)

