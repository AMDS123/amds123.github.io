---
layout: post
title: "Cover Song Synthesis by Analogy"
date: 2018-06-17 08:09:20
categories: arXiv_SD
tags: arXiv_SD Style_Transfer CNN
author: Christopher J. Tralie
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we pose and address the following "cover song analogies" problem: given a song A by artist 1 and a cover song A' of this song by artist 2, and given a different song B by artist 1, synthesize a song B' which is a cover of B in the style of artist 2. Normally, such a polyphonic style transfer problem would be quite challenging, but we show how the cover songs example constrains the problem, making it easier to solve. First, we extract the longest common beat-synchronous subsequence between A and A', and we time stretch the corresponding beat intervals in A' so that they align with A. We then derive a version of joint 2D convolutional NMF, which we apply to the constant-Q spectrograms of the synchronized segments to learn a translation dictionary of sound templates from A to A'. Finally, we apply the learned templates as filters to the song B, and we mash up the translated filtered components into the synthesized song B' using audio mosaicing. We showcase our algorithm on several examples, including a synthesized cover version of Michael Jackson's "Bad" by Alien Ant Farm, learned from the latter's "Smooth Criminal" cover.'

##### Abstract (translated by Google)
在这项工作中，我们提出并解决了以下“封面歌曲类比”问题：由艺术家1给出歌曲A，由艺术家2给出该歌曲的封面歌曲A'，并由艺术家1给出不同的歌曲B，合成歌曲B'，它是B的风格，是艺术家2的封面。通常，这种复调风格的转换问题会非常具有挑战性，但我们将展示封面歌曲示例如何约束问题，使其更易于解决。首先，我们提取A和A'之间最长的共同节拍同步子序列，然后我们在A'中延长相应的拍子间隔，使它们与A对齐。然后，我们推导出联合2D卷积NMF的一个版本，我们将其应用于同步段的常数-Q谱图以学习从A到A'的声音模板的翻译词典。最后，我们将学习的模板作为过滤器应用于歌曲B，并且使用音频拼接将翻译过的分量混合到合成歌曲B'中。我们在几个例子中展示了我们的算法，其中包括由Alien Ant Farm合成的迈克尔杰克逊的“坏”封面版，从后者的“平滑刑事”封面中学到。

##### URL
[http://arxiv.org/abs/1806.06347](http://arxiv.org/abs/1806.06347)

##### PDF
[http://arxiv.org/pdf/1806.06347](http://arxiv.org/pdf/1806.06347)

