---
layout: post
title: "Branched Multi-Task Networks: Deciding What Layers To Share"
date: 2019-04-05 08:00:32
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Simon Vandenhende, Bert De Brabandere, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
In the context of deep learning, neural networks with multiple branches have been used that each solve different tasks. Such ramified networks typically start with a number of shared layers, after which different tasks branch out into their own sequence of layers. As the number of possible network configurations is combinatorially large, prior work has often relied on ad hoc methods to determine the level of layer sharing. This work proposes a novel method to assess the relatedness of tasks in a principled way. We base the relatedness of a task pair on the usefulness of a set of features of one task for the other, and vice versa. The resulting task affinities are used for the automated construction of a branched multi-task network in which deeper layers gradually grow more task-specific. Our multi-task network outperforms the state-of-the-art on CelebA. Additionally, the layer sharing schemes devised by our method outperform common multi-task learning models which were constructed ad hoc. We include additional experiments on Cityscapes and SUN RGB-D to illustrate the wide applicability of our approach. Code and trained models for this paper are made available this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02920](https://arxiv.org/abs/1904.02920)

##### PDF
[https://arxiv.org/pdf/1904.02920](https://arxiv.org/pdf/1904.02920)

