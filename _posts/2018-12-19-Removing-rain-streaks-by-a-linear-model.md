---
layout: post
title: "Removing rain streaks by a linear model"
date: 2018-12-19 10:51:50
categories: arXiv_CV
tags: arXiv_CV Attention Detection
author: Yinglong Wang, Shuaicheng Liu, Bing Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
Removing rain streaks from a single image continues to draw attentions today in outdoor vision systems. In this paper, we present an efficient method to remove rain streaks. First, the location map of rain pixels needs to be known as precisely as possible, to which we implement a relatively accurate detection of rain streaks by utilizing two characteristics of rain streaks.The key component of our method is to represent the intensity of each detected rain pixel using a linear model: $p=\alpha s + \beta$, where $p$ is the observed intensity of a rain pixel and $s$ represents the intensity of the background (i.e., before rain-affected). To solve $\alpha$ and $\beta$ for each detected rain pixel, we concentrate on a window centered around it and form an $L_2$-norm cost function by considering all detected rain pixels within the window, where the corresponding rain-removed intensity of each detected rain pixel is estimated by some neighboring non-rain pixels. By minimizing this cost function, we determine $\alpha$ and $\beta$ so as to construct the final rain-removed pixel intensity. Compared with several state-of-the-art works, our proposed method can remove rain streaks from a single color image much more efficiently - it offers not only a better visual quality but also a speed-up of several times to one degree of magnitude.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07870](http://arxiv.org/abs/1812.07870)

##### PDF
[http://arxiv.org/pdf/1812.07870](http://arxiv.org/pdf/1812.07870)

