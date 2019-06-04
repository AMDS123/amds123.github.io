---
layout: post
title: "Temporally Coherent Full 3D Mesh Human Pose Recovery from Monocular Video"
date: 2019-06-01 06:39:35
categories: arXiv_CV
tags: arXiv_CV Face RNN Deep_Learning Quantitative
author: Jian Liu, Naveed Akhtar, Ajmal Mian
mathjax: true
---

* content
{:toc}

##### Abstract
Advances in Deep Learning have recently made it possible to recover full 3D meshes of human poses from individual images. However, extension of this notion to videos for recovering temporally coherent poses still remains unexplored. A major challenge in this regard is the lack of appropriately annotated video data for learning the desired deep models. Existing human pose datasets only provide 2D or 3D skeleton joint annotations, whereas the datasets are also recorded in constrained environments. We first contribute a technique to synthesize monocular action videos with rich 3D annotations that are suitable for learning computational models for full mesh 3D human pose recovery. Compared to the existing methods which simply "texture-map" clothes onto the 3D human pose models, our approach incorporates Physics based realistic cloth deformations with the human body movements. The generated videos cover a large variety of human actions, poses, and visual appearances, whereas the annotations record accurate human pose dynamics and human body surface information. Our second major contribution is an end-to-end trainable Recurrent Neural Network for full pose mesh recovery from monocular video. Using the proposed video data and LSTM based recurrent structure, our network explicitly learns to model the temporal coherence in videos and imposes geometric consistency over the recovered meshes. We establish the effectiveness of the proposed model with quantitative and qualitative analysis using the proposed and benchmark datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00161](http://arxiv.org/abs/1906.00161)

##### PDF
[http://arxiv.org/pdf/1906.00161](http://arxiv.org/pdf/1906.00161)

