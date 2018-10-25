---
layout: post
title: "Learning to Segment Inputs for NMT Favors Character-Level Processing"
date: 2018-10-24 10:21:05
categories: arXiv_CL
tags: arXiv_CL Segmentation NMT
author: Julia Kreutzer, Artem Sokolov
mathjax: true
---

* content
{:toc}

##### Abstract
Most modern neural machine translation (NMT) systems rely on presegmented inputs. Segmentation granularity importantly determines the input and output sequence lengths, hence the modeling depth, and source and target vocabularies, which in turn determine model size, computational costs of softmax normalization, and handling of out-of-vocabulary words. However, the current practice is to use static, heuristic-based segmentations that are fixed before NMT training. This begs the question whether the chosen segmentation is optimal for the translation task. To overcome suboptimal segmentation choices, we present an algorithm for dynamic segmentation based on the Adaptative Computation Time algorithm (Graves 2016), that is trainable end-to-end and driven by the NMT objective. In an evaluation on four translation tasks we found that, given the freedom to navigate between different segmentation levels, the model prefers to operate on (almost) character level, providing support for purely character-level NMT models from a novel angle.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.01480](https://arxiv.org/abs/1810.01480)

##### PDF
[https://arxiv.org/pdf/1810.01480](https://arxiv.org/pdf/1810.01480)

