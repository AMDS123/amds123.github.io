---
layout: post
title: "View Selection with Geometric Uncertainty Modeling"
date: 2018-02-25 23:46:34
categories: arXiv_CV
tags: arXiv_CV
author: Cheng Peng, Volkan Isler
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating positions of world points from features observed in images is a key problem in 3D reconstruction, image mosaicking,simultaneous localization and mapping and structure from motion. We consider a special instance in which there is a dominant ground plane $\mathcal{G}$ viewed from a parallel viewing plane $\mathcal{S}$ above it. Such instances commonly arise, for example, in aerial photography. Consider a world point $g \in \mathcal{G}$ and its worst case reconstruction uncertainty $\varepsilon(g,\mathcal{S})$ obtained by merging \emph{all} possible views of $g$ chosen from $\mathcal{S}$. We first show that one can pick two views $s_p$ and $s_q$ such that the uncertainty $\varepsilon(g,\{s_p,s_q\})$ obtained using only these two views is almost as good as (i.e. within a small constant factor of) $\varepsilon(g,\mathcal{S})$. Next, we extend the result to the entire ground plane $\mathcal{G}$ and show that one can pick a small subset of $\mathcal{S'} \subseteq \mathcal{S}$ (which grows only linearly with the area of $\mathcal{G}$) and still obtain a constant factor approximation, for every point $g \in \mathcal{G}$, to the minimum worst case estimate obtained by merging all views in $\mathcal{S}$. Finally, we present a multi-resolution view selection method which extends our techniques to non-planar scenes. We show that the method can produce rich and accurate dense reconstructions with a small number of views. Our results provide a view selection mechanism with provable performance guarantees which can drastically increase the speed of scene reconstruction algorithms. In addition to theoretical results, we demonstrate their effectiveness in an application where aerial imagery is used for monitoring farms and orchards.

##### Abstract (translated by Google)
根据在图像中观察到的特征来估计世界点的位置是3D重建，图像镶嵌，同时定位和映射以及来自运动的结构中的关键问题。我们考虑一个特殊的例子，其中有一个占主导地面的平面$ \ mathcal {G} $从平行观看平面$ \ mathcal {S} $上面查看。例如，这种情况通常出现在航空摄影中。考虑一个世界点$ g \ in \ mathcal {G} $和其最坏情况重构不确定性$ \ varepsilon（g，\ mathcal {S}）$通过合并\ emph {all} \ mathcal {S} $。我们首先表明可以选择两个视图$ s_p $和$ s_q $，这样仅使用这两个视图获得的不确定性$ \ varepsilon（g，\ {s_p，s_q \}）$几乎一样好（即在一个小常数因子）\ \ varepsilon（g，\ mathcal {S}）$。接下来，我们将结果扩展到整个地平面$ \ mathcal {G} $，并表明可以选择一小部分$ \ mathcal {S'} \ subseteq \ mathcal {S} $（它只与对于\ mathcal {G} $中的每个点$ g \，通过合并$ \ mathcal {S}中的所有视图获得的最小最坏情况估计，仍然获得常数因子近似， $。最后，我们提出了一个多分辨率视图选择方法，它将我们的技术扩展到非平面场景。我们表明，该方法可以产生丰富和准确的密集重建与少量的意见。我们的结果提供了一个可视性选择机制和可证明的性能保证，可以大大提高场景重建算法的速度。除了理论结果，我们还展示了它们在航空影像用于监测农场和果园的应用中的有效性。

##### URL
[http://arxiv.org/abs/1704.00085](http://arxiv.org/abs/1704.00085)

##### PDF
[http://arxiv.org/pdf/1704.00085](http://arxiv.org/pdf/1704.00085)

