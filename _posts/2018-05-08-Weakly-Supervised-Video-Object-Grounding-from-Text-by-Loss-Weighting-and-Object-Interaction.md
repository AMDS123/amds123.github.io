---
layout: post
title: "Weakly-Supervised Video Object Grounding from Text by Loss Weighting and Object Interaction"
date: 2018-05-08 05:05:56
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Luowei Zhou, Nathan Louis, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
We study weakly-supervised video object grounding: given a video segment and a corresponding descriptive sentence, the goal is to localize objects that are mentioned in the sentence in the video. During training, no object bounding boxes are available, but the set of possible objects to be grounded is known beforehand. Existing approaches in the image domain use Multiple Instance Learning (MIL) to ground objects by enforcing matches between visual and semantic features. A naive extension of this approach to the video domain is to treat the entire segment as a bag of spatial object proposals. However, an object existing sparsely across multiple frames might not be detected completely since successfully spotting it from one single frame would trigger a satisfactory match. To this end, we propagate the weak supervisory signal from the segment level to frames that likely contain the target object. For frames that are unlikely to contain the target objects, we use an alternative penalty loss. We also leverage the interactions among objects as a textual guide for the grounding. We evaluate our model on the newly-collected benchmark YouCook2-BoundingBox and show improvements over competitive baselines.

##### Abstract (translated by Google)
我们研究弱监督的视频对象的基础：给定一个视频片段和一个相应的描述性句子，目标是定位视频中句子中提到的对象。在训练过程中，没有可用的对象边界框，但可以预先知道要接地的一组可能的对象。图像域中的现有方法使用多实例学习（MIL）通过强化视觉和语义特征之间的匹配来对对象进行研磨。对视频域的这种方法的一种无知扩展是将整个分段视为一袋空间对象提议。但是，跨多个帧稀疏地存在的对象可能无法完全检测到，因为从一个单帧中成功地发现它会触发令人满意的匹配。为此，我们将弱监控信号从段级传播到可能包含目标对象的帧。对于不太可能包含目标对象的帧，我们使用另一种损失损失。我们还利用对象之间的交互作为基础的文本指南。我们在新收集的基准YouCook2-BoundingBox上评估我们的模型，并显示出在竞争基线方面的改进。

##### URL
[https://arxiv.org/abs/1805.02834](https://arxiv.org/abs/1805.02834)

##### PDF
[https://arxiv.org/pdf/1805.02834](https://arxiv.org/pdf/1805.02834)

