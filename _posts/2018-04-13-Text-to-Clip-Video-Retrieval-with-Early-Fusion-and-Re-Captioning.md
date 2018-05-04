---
layout: post
title: "Text-to-Clip Video Retrieval with Early Fusion and Re-Captioning"
date: 2018-04-13 20:46:37
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption Embedding
author: Huijuan Xu, Kun He, Leonid Sigal, Stan Sclaroff, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method capable of retrieving clips from untrimmed videos based on natural language queries. This cross-modal retrieval task plays a key role in visual-semantic understanding, and requires localizing clips in time and computing their similarity to the query sentence. Current methods generate sentence and video embeddings and then compare them using a late fusion approach, but this ignores the word order in queries and prevents more fine-grained comparisons. Motivated by the need for fine-grained multi-modal feature fusion, we propose a novel early fusion embedding approach that combines video and language information at the word level. Furthermore, we use the inverse task of dense video captioning as a side-task to improve the learned embedding. Our full model combines these components with an efficient proposal pipeline that performs accurate localization of potential video clips. We present a comprehensive experimental validation on two large-scale text-to-clip datasets (Charades-STA and DiDeMo) and attain state-of-the-art retrieval results with our model.

##### Abstract (translated by Google)
我们提出了一种新颖的方法，能够根据自然语言查询从未修剪的视频中检索剪辑。这种跨模式检索任务在视觉 - 语义理解中起着关键作用，并且需要及时定位剪辑并计算它们与查询句子的相似性。目前的方法可以生成句子和视频嵌入，然后使用后期融合方法进行比较，但是这会忽略查询中的单词顺序并阻止更细粒度的比较。受到对细粒度多模式特征融合的需求的启发，我们提出了一种新颖的融合嵌入方法，该方法在字级别结合视频和语言信息。此外，我们使用密集视频字幕的逆向任务作为改进学习嵌入的侧面任务。我们的完整模型将这些组件与高效的提案管道相结合，可以对潜在视频剪辑进行精确定位。我们对两个大规模的文本到剪辑数据集（Charades-STA和DiDeMo）进行了全面的实验验证，并使用我们的模型获得了最先进的检索结果。

##### URL
[https://arxiv.org/abs/1804.05113](https://arxiv.org/abs/1804.05113)

##### PDF
[https://arxiv.org/pdf/1804.05113](https://arxiv.org/pdf/1804.05113)

