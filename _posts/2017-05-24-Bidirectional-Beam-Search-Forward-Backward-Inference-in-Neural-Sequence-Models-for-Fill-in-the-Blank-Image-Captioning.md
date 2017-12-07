---
layout: post
title: "Bidirectional Beam Search: Forward-Backward Inference in Neural Sequence Models for Fill-in-the-Blank Image Captioning"
date: 2017-05-24 13:42:47
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption
author: Qing Sun, Stefan Lee, Dhruv Batra
mathjax: true
---

* content
{:toc}

##### Abstract
We develop the first approximate inference algorithm for 1-Best (and M-Best) decoding in bidirectional neural sequence models by extending Beam Search (BS) to reason about both forward and backward time dependencies. Beam Search (BS) is a widely used approximate inference algorithm for decoding sequences from unidirectional neural sequence models. Interestingly, approximate inference in bidirectional models remains an open problem, despite their significant advantage in modeling information from both the past and future. To enable the use of bidirectional models, we present Bidirectional Beam Search (BiBS), an efficient algorithm for approximate bidirectional inference.To evaluate our method and as an interesting problem in its own right, we introduce a novel Fill-in-the-Blank Image Captioning task which requires reasoning about both past and future sentence structure to reconstruct sensible image descriptions. We use this task as well as the Visual Madlibs dataset to demonstrate the effectiveness of our approach, consistently outperforming all baseline methods.

##### Abstract (translated by Google)
我们通过扩展Beam Search（BS）来推导关于前向和后向时间依赖性的第一个近似推理算法，用于双向神经序列模型中的1-Best（和M-Best）解码。束搜索（BS）是一种广泛使用的近似推理算法，用于解码单向神经序列模型的序列。有趣的是，双向模型的近似推理仍然是一个悬而未决的问题，尽管它们在过去和未来的信息建模方面具有显着的优势。为了能够使用双向模型，我们提出了双向光束搜索（BiBS），一种有效的近似双向推理算法。为了评估我们的方法和作为一个有趣的问题，我们引入了一个新颖的填充空白图像标题任务需要对过去和将来的句子结构进行推理来重建合理的图像描述。我们使用这个任务以及Visual Madlibs数据集来证明我们的方法的有效性，始终优于所有的基线方法。

##### URL
[https://arxiv.org/abs/1705.08759](https://arxiv.org/abs/1705.08759)

##### PDF
[https://arxiv.org/pdf/1705.08759](https://arxiv.org/pdf/1705.08759)

