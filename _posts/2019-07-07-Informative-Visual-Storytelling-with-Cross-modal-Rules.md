---
layout: post
title: "Informative Visual Storytelling with Cross-modal Rules"
date: 2019-07-07 07:41:59
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Inference
author: Jiacheng Li, Haizhou Shi, Siliang Tang, Fei Wu, Yueting Zhuang
mathjax: true
---

* content
{:toc}

##### Abstract
Existing methods in the Visual Storytelling field often suffer from the problem of generating general descriptions, while the image contains a lot of meaningful contents remaining unnoticed. The failure of informative story generation can be concluded to the model's incompetence of capturing enough meaningful concepts. The categories of these concepts include entities, attributes, actions, and events, which are in some cases crucial to grounded storytelling. To solve this problem, we propose a method to mine the cross-modal rules to help the model infer these informative concepts given certain visual input. We first build the multimodal transactions by concatenating the CNN activations and the word indices. Then we use the association rule mining algorithm to mine the cross-modal rules, which will be used for the concept inference. With the help of the cross-modal rules, the generated stories are more grounded and informative. Besides, our proposed method holds the advantages of interpretation, expandability, and transferability, indicating potential for wider application. Finally, we leverage these concepts in our encoder-decoder framework with the attention mechanism. We conduct several experiments on the VIsual StoryTelling~(VIST) dataset, the results of which demonstrate the effectiveness of our approach in terms of both automatic metrics and human evaluation. Additional experiments are also conducted showing that our mined cross-modal rules as additional knowledge helps the model gain better performance when trained on a small dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03240](http://arxiv.org/abs/1907.03240)

##### PDF
[http://arxiv.org/pdf/1907.03240](http://arxiv.org/pdf/1907.03240)

