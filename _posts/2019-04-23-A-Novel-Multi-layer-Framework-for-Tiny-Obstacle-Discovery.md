---
layout: post
title: "A Novel Multi-layer Framework for Tiny Obstacle Discovery"
date: 2019-04-23 05:54:30
categories: arXiv_CV
tags: arXiv_CV
author: Feng Xue, Anlong Ming, Menghan Zhou, Yu Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
For tiny obstacle discovery in a monocular image, edge is a fundamental visual element. Nevertheless, because of various reasons, e.g., noise and similar color distribution with background, it is still difficult to detect the edges of tiny obstacles at long distance. In this paper, we propose an obstacle-aware discovery method to recover the missing contours of these obstacles, which helps to obtain obstacle proposals as much as possible. First, by using visual cues in monocular images, several multi-layer regions are elaborately inferred to reveal the distances from the camera. Second, several novel obstacle-aware occlusion edge maps are constructed to well capture the contours of tiny obstacles, which combines cues from each layer. Third, to ensure the existence of the tiny obstacle proposals, the maps from all layers are used for proposals extraction. Finally, based on these proposals containing tiny obstacles, a novel obstacle-aware regressor is proposed to generate an obstacle occupied probability map with high confidence. The convincing experimental results with comparisons on the Lost and Found dataset demonstrate the effectiveness of our approach, achieving around 9.5% improvement on the accuracy than FPHT and PHT, it even gets comparable performance to MergeNet. Moreover, our method outperforms the state-of-the-art algorithms and significantly improves the discovery ability for tiny obstacles at long distance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10161](http://arxiv.org/abs/1904.10161)

##### PDF
[http://arxiv.org/pdf/1904.10161](http://arxiv.org/pdf/1904.10161)

