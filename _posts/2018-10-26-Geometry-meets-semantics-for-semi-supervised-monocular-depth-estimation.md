---
layout: post
title: "Geometry meets semantics for semi-supervised monocular depth estimation"
date: 2018-10-26 14:39:37
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference Deep_Learning Prediction
author: Pierluigi Zama Ramirez, Matteo Poggi, Fabio Tosi, Stefano Mattoccia, Luigi Di Stefano
mathjax: true
---

* content
{:toc}

##### Abstract
Depth estimation from a single image represents a very exciting challenge in computer vision. While other image-based depth sensing techniques leverage on the geometry between different viewpoints (e.g., stereo or structure from motion), the lack of these cues within a single image renders ill-posed the monocular depth estimation task. For inference, state-of-the-art encoder-decoder architectures for monocular depth estimation rely on effective feature representations learned at training time. For unsupervised training of these models, geometry has been effectively exploited by suitable images warping losses computed from views acquired by a stereo rig or a moving camera. In this paper, we make a further step forward showing that learning semantic information from images enables to improve effectively monocular depth estimation as well. In particular, by leveraging on semantically labeled images together with unsupervised signals gained by geometry through an image warping loss, we propose a deep learning approach aimed at joint semantic segmentation and depth estimation. Our overall learning framework is semi-supervised, as we deploy groundtruth data only in the semantic domain. At training time, our network learns a common feature representation for both tasks and a novel cross-task loss function is proposed. The experimental findings show how, jointly tackling depth prediction and semantic segmentation, allows to improve depth estimation accuracy. In particular, on the KITTI dataset our network outperforms state-of-the-art methods for monocular depth estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.04093](http://arxiv.org/abs/1810.04093)

##### PDF
[http://arxiv.org/pdf/1810.04093](http://arxiv.org/pdf/1810.04093)

