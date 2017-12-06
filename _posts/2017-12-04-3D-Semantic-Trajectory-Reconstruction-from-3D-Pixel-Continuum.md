---
layout: post
title: "3D Semantic Trajectory Reconstruction from 3D Pixel Continuum"
date: 2017-12-04 21:03:12
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Jae Shin Yoon, Ziwei Li, Hyun Soo Park
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method to reconstruct dense semantic trajectory stream of human interactions in 3D from synchronized multiple videos. The interactions inherently introduce self-occlusion and illumination/appearance/shape changes, resulting in highly fragmented trajectory reconstruction with noisy and coarse semantic labels. Our conjecture is that among many views, there exists a set of views that can confidently recognize the visual semantic label of a 3D trajectory. We introduce a new representation called 3D semantic map---a probability distribution over the semantic labels per trajectory. We construct the 3D semantic map by reasoning about visibility and 2D recognition confidence based on view-pooling, i.e., finding the view that best represents the semantics of the trajectory. Using the 3D semantic map, we precisely infer all trajectory labels jointly by considering the affinity between long range trajectories via estimating their local rigid transformations. This inference quantitatively outperforms the baseline approaches in terms of predictive validity, representation robustness, and affinity effectiveness. We demonstrate that our algorithm can robustly compute the semantic labels of a large scale trajectory set involving real-world human interactions with object, scenes, and people.

##### Abstract (translated by Google)
本文提出了一种从同步多个视频重建人类交互密集语义轨迹流的方法。这种相互作用固有地引入了自我遮挡和光照/外观/形状变化，导致高度碎片化的轨迹重构，带有嘈杂和粗糙的语义标签。我们的猜想是，在许多观点中，存在一组能够自信地识别3D轨迹的视觉语义标签的观点。我们引入了一种称为3D语义映射的新表示---每个轨迹的语义标签的概率分布。我们通过基于视图合并的可视性和2D识别置信度来推理3D语义映射，即找到最能代表轨迹语义的视图。使用3D语义映射，我们通过估计它们的局部刚性变换来考虑长程轨迹之间的相关性，从而精确地推断所有轨迹标记。这种推断在数量上比预测有效性，表示鲁棒性和亲和力有效性方面的基准方法更胜一筹。我们证明，我们的算法可以强大地计算涉及与对象，场景和人物的真实世界人类交互的大规模轨迹集合的语义标签。

##### URL
[http://arxiv.org/abs/1712.01359](http://arxiv.org/abs/1712.01359)

