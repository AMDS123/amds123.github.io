---
layout: post
title: "Weakly-supervised Action Localization with Background Modeling"
date: 2019-08-19 01:33:14
categories: arXiv_CV
tags: arXiv_CV Attention
author: Phuc Xuan Nguyen, Deva Ramanan, Charless C. Fowlkes
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a latent approach that learns to detect actions in long sequences given training videos with only whole-video class labels. Our approach makes use of two innovations to attention-modeling in weakly-supervised learning. First, and most notably, our framework uses an attention model to extract both foreground and background frames whose appearance is explicitly modeled. Most prior works ignore the background, but we show that modeling it allows our system to learn a richer notion of actions and their temporal extents. Second, we combine bottom-up, class-agnostic attention modules with top-down, class-specific activation maps, using the latter as form of self-supervision for the former. Doing so allows our model to learn a more accurate model of attention without explicit temporal supervision. These modifications lead to 10% AP@IoU=0.5 improvement over existing systems on THUMOS14. Our proposed weaklysupervised system outperforms recent state-of-the-arts by at least 4.3% AP@IoU=0.5. Finally, we demonstrate that weakly-supervised learning can be used to aggressively scale-up learning to in-the-wild, uncurated Instagram videos. The addition of these videos significantly improves localization performance of our weakly-supervised model

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06552](http://arxiv.org/abs/1908.06552)

##### PDF
[http://arxiv.org/pdf/1908.06552](http://arxiv.org/pdf/1908.06552)

