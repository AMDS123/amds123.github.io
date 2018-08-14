---
layout: post
title: "Language Style Transfer from Sentences with Arbitrary Unknown Styles"
date: 2018-08-13 06:08:45
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Style_Transfer
author: Yanpeng Zhao, Wei Bi, Deng Cai, Xiaojiang Liu, Kewei Tu, Shuming Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Language style transfer is the problem of migrating the content of a source sentence to a target style. In many of its applications, parallel training data are not available and source sentences to be transferred may have arbitrary and unknown styles. First, each sentence is encoded into its content and style latent representations. Then, by recombining the content with the target style, we decode a sentence aligned in the target domain. To adequately constrain the encoding and decoding functions, we couple them with two loss functions. The first is a style discrepancy loss, enforcing that the style representation accurately encodes the style information guided by the discrepancy between the sentence style and the target style. The second is a cycle consistency loss, which ensures that the transferred sentence should preserve the content of the original sentence disentangled from its style. We validate the effectiveness of our model in three tasks: sentiment modification of restaurant reviews, dialog response revision with a romantic style, and sentence rewriting with a Shakespearean style.

##### Abstract (translated by Google)
语言样式转移是将源句子的内容迁移到目标样式的问题。在许多应用程序中，并行训练数据不可用，要传输的源句可能具有任意和未知的样式。首先，每个句子被编码为其内容和风格潜在表示。然后，通过将内容与目标样式重新组合，我们解码在目标域中对齐的句子。为了充分限制编码和解码功能，我们将它们与两个损失函数耦合在一起。第一种是样式差异丢失，强制样式表示准确地编码由句型和目标样式之间的差异引导的样式信息。第二个是循环一致性损失，它确保转移的句子应该保留原始句子的内容从其风格中解开。我们在三个任务中验证了我们模型的有效性：餐厅评论的情绪修改，浪漫风格的对话响应修订，以及莎士比亚风格的句子重写。

##### URL
[http://arxiv.org/abs/1808.04071](http://arxiv.org/abs/1808.04071)

##### PDF
[http://arxiv.org/pdf/1808.04071](http://arxiv.org/pdf/1808.04071)

