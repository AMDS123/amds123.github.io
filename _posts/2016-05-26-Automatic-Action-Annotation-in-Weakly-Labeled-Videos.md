---
layout: post
title: "Automatic Action Annotation in Weakly Labeled Videos"
date: 2016-05-26 02:22:57
categories: arXiv_CV
tags: arXiv_CV Salient Weakly_Supervised
author: Waqas Sultani, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Manual spatio-temporal annotation of human action in videos is laborious, requires several annotators and contains human biases. In this paper, we present a weakly supervised approach to automatically obtain spatio-temporal annotations of an actor in action videos. We first obtain a large number of action proposals in each video. To capture a few most representative action proposals in each video and evade processing thousands of them, we rank them using optical flow and saliency in a 3D-MRF based framework and select a few proposals using MAP based proposal subset selection method. We demonstrate that this ranking preserves the high quality action proposals. Several such proposals are generated for each video of the same action. Our next challenge is to iteratively select one proposal from each video so that all proposals are globally consistent. We formulate this as Generalized Maximum Clique Graph problem using shape, global and fine grained similarity of proposals across the videos. The output of our method is the most action representative proposals from each video. Our method can also annotate multiple instances of the same action in a video. We have validated our approach on three challenging action datasets: UCF Sport, sub-JHMDB and THUMOS'13 and have obtained promising results compared to several baseline methods. Moreover, on UCF Sports, we demonstrate that action classifiers trained on these automatically obtained spatio-temporal annotations have comparable performance to the classifiers trained on ground truth annotation.

##### Abstract (translated by Google)
在视频中人为操作的手动时空诠释是费力的，需要几个注释者并且包含人类的偏见。在本文中，我们提出了一个弱监督的方法来自动获取演员在动作视频中的时空注释。我们首先在每个视频中获得大量的行动建议。为了在每个视频中捕捉几个最具代表性的行动建议，并避免处理成千上万的视频，我们使用基于3D-MRF的框架中的光流和显着性来对它们进行排序，并使用基于MAP的提案子集选择方法来选择一些提议。我们证明这个排名保留了高质量的行动建议。针对同一动作的每个视频都会生成几个这样的提议。我们的下一个挑战是从每个视频迭代选择一个提案，以便所有提案在全球范围内一致。我们把这个作为广义最大集团图形问题，用形状，全局和精细粒度的视频相似度来表示。我们的方法的输出是每个视频中最有代表性的提案。我们的方法也可以在视频中注释同一动作的多个实例。我们已经验证了我们在三个具有挑战性的行动数据集上的方法：UCF体育，子JHMDB和THUMOS'13，并取得了令人鼓舞的结果相比，几个基准的方法。此外，在UCF体育，我们表明，对这些自动获得的时空注释进行训练的行动分类器具有相似的性能与在地面真值注释上训练的分类器。

##### URL
[https://arxiv.org/abs/1605.08125](https://arxiv.org/abs/1605.08125)

##### PDF
[https://arxiv.org/pdf/1605.08125](https://arxiv.org/pdf/1605.08125)

