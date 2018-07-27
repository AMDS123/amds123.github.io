---
layout: post
title: "Move Forward and Tell: A Progressive Generator of Video Descriptions"
date: 2018-07-26 08:57:24
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption Embedding
author: Yilei Xiong, Bo Dai, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
We present an efficient framework that can generate a coherent paragraph to describe a given video. Previous works on video captioning usually focus on video clips. They typically treat an entire video as a whole and generate the caption conditioned on a single embedding. On the contrary, we consider videos with rich temporal structures and aim to generate paragraph descriptions that can preserve the story flow while being coherent and concise. Towards this goal, we propose a new approach, which produces a descriptive paragraph by assembling temporally localized descriptions. Given a video, it selects a sequence of distinctive clips and generates sentences thereon in a coherent manner. Particularly, the selection of clips and the production of sentences are done jointly and progressively driven by a recurrent network -- what to describe next depends on what have been said before. Here, the recurrent network is learned via self-critical sequence training with both sentence-level and paragraph-level rewards. On the ActivityNet Captions dataset, our method demonstrated the capability of generating high-quality paragraph descriptions for videos. Compared to those by other methods, the descriptions produced by our method are often more relevant, more coherent, and more concise.

##### Abstract (translated by Google)
我们提出了一个有效的框架，可以生成一个连贯的段落来描述给定的视频。以前关于视频字幕的工作通常关注视频剪辑。它们通常将整个视频作为一个整体处理，并生成以单个嵌入为条件的标题。相反，我们考虑具有丰富时间结构的视频，旨在生成段落描述，以保持故事流程，同时保持连贯和简洁。为实现这一目标，我们提出了一种新方法，通过组合时间本地化描述来生成描述性段落。给定视频，它选择一系列独特的剪辑并以连贯的方式在其上生成句子。特别是，剪辑的选择和句子的制作是由一个经常性的网络联合起来并逐步推动的 - 接下来要描述的内容取决于之前所说的内容。在这里，循环网络是通过自我批判序列训练学习的，包括句子级别和段落级别的奖励。在ActivityNet Captions数据集上，我们的方法展示了为视频生成高质量段落描述的功能。与其他方法相比，我们的方法产生的描述通常更相关，更连贯，更简洁。

##### URL
[http://arxiv.org/abs/1807.10018](http://arxiv.org/abs/1807.10018)

##### PDF
[http://arxiv.org/pdf/1807.10018](http://arxiv.org/pdf/1807.10018)

