---
layout: post
title: "Point2Sequence: Learning the Shape Representation of 3D Point Clouds with an Attention-based Sequence to Sequence Network"
date: 2018-11-06 15:07:03
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention RNN Classification Deep_Learning Relation
author: Xinhai Liu, Zhizhong Han, Yu-Shen Liu, Matthias Zwicker
mathjax: true
---

* content
{:toc}

##### Abstract
Exploring contextual information in the local region is important for shape understanding and analysis. Existing studies often employ hand-crafted or explicit ways to encode contextual information of local regions. However, it is hard to capture fine-grained contextual information in hand-crafted or explicit manners, such as the correlation between different areas in a local region, which limits the discriminative ability of learned features. To resolve this issue, we propose a novel deep learning model for 3D point clouds, named Point2Sequence, to learn 3D shape features by capturing fine-grained contextual information in a novel implicit way. Point2Sequence employs a novel sequence learning model for point clouds to capture the correlations by aggregating multi-scale areas of each local region with attention. Specifically, Point2Sequence first learns the feature of each area scale in a local region. Then, it captures the correlation between area scales in the process of aggregating all area scales using a recurrent neural network (RNN) based encoder-decoder structure, where an attention mechanism is proposed to highlight the importance of different area scales. Experimental results show that Point2Sequence achieves state-of-the-art performance in shape classification and segmentation tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02565](http://arxiv.org/abs/1811.02565)

##### PDF
[http://arxiv.org/pdf/1811.02565](http://arxiv.org/pdf/1811.02565)

