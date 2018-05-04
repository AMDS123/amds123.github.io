---
layout: post
title: "End-to-End Dense Video Captioning with Masked Transformer"
date: 2018-04-03 04:11:00
categories: arXiv_CV
tags: arXiv_CV Video_Caption Attention Caption
author: Luowei Zhou, Yingbo Zhou, Jason J. Corso, Richard Socher, Caiming Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Dense video captioning aims to generate text descriptions for all events in an untrimmed video. This involves both detecting and describing events. Therefore, all previous methods on dense video captioning tackle this problem by building two models, i.e. an event proposal and a captioning model, for these two sub-problems. The models are either trained separately or in alternation. This prevents direct influence of the language description to the event proposal, which is important for generating accurate descriptions. To address this problem, we propose an end-to-end transformer model for dense video captioning. The encoder encodes the video into appropriate representations. The proposal decoder decodes from the encoding with different anchors to form video event proposals. The captioning decoder employs a masking network to restrict its attention to the proposal event over the encoding feature. This masking network converts the event proposal to a differentiable mask, which ensures the consistency between the proposal and captioning during training. In addition, our model employs a self-attention mechanism, which enables the use of efficient non-recurrent structure during encoding and leads to performance improvements. We demonstrate the effectiveness of this end-to-end model on ActivityNet Captions and YouCookII datasets, where we achieved 10.12 and 6.58 METEOR score, respectively.

##### Abstract (translated by Google)
密集视频字幕旨在为未修剪的视频中的所有事件生成文字说明。这涉及检测和描述事件。因此，以前所有关于密集视频字幕的方法通过为这两个子问题构建两个模型（即事件提议和字幕模型）来解决这个问题。模型可以单独或交替进行训练。这可以防止语言描述直接影响事件提议，这对于生成准确的描述非常重要。为了解决这个问题，我们提出了一种用于密集视频字幕的端到端变压器模型。编码器将视频编码为适当的表示。提议解码器从具有不同锚点的编码中解码以形成视频事件提议。字幕解码器使用掩蔽网络将其注意力限制在编码特征上的提议事件上。该屏蔽网络将事件提议转换为可区分的掩码，以确保提案和字幕在训练期间的一致性。此外，我们的模型采用了自我注意机制，可以在编码过程中使用高效的非循环结构，并且可以提高性能。我们在ActivityNet Captions和YouCookII数据集上展示了这种端到端模型的有效性，我们分别获得了10.12和6.58个METEOR得分。

##### URL
[https://arxiv.org/abs/1804.00819](https://arxiv.org/abs/1804.00819)

##### PDF
[https://arxiv.org/pdf/1804.00819](https://arxiv.org/pdf/1804.00819)

