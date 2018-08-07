---
layout: post
title: "Speaking the Same Language: Matching Machine to Human Captions by Adversarial Training"
date: 2017-11-06 15:43:47
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Caption
author: Rakshith Shetty, Marcus Rohrbach, Lisa Anne Hendricks, Mario Fritz, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
While strong progress has been made in image captioning over the last years, machine and human captions are still quite distinct. A closer look reveals that this is due to the deficiencies in the generated word distribution, vocabulary size, and strong bias in the generators towards frequent captions. Furthermore, humans -- rightfully so -- generate multiple, diverse captions, due to the inherent ambiguity in the captioning task which is not considered in today's systems. To address these challenges, we change the training objective of the caption generator from reproducing groundtruth captions to generating a set of captions that is indistinguishable from human generated captions. Instead of handcrafting such a learning target, we employ adversarial training in combination with an approximate Gumbel sampler to implicitly match the generated distribution to the human one. While our method achieves comparable performance to the state-of-the-art in terms of the correctness of the captions, we generate a set of diverse captions, that are significantly less biased and match the word statistics better in several aspects.

##### Abstract (translated by Google)
虽然过去几年在图像字幕方面取得了很大进展，但机器和人工字幕仍然十分鲜明。仔细观察发现，这是由于生成的单词分布，词汇量大小以及生成器对频繁标题的强烈偏见所造成的不足。此外，人类 - 理所当然 - 产生多个不同的字幕，因为字幕任务固有的模糊性在今天的系统中没有考虑到。为了应对这些挑战，我们将字幕生成器的培训目标从再现地面字幕改为生成一组与人类生成的字幕无法区分的字幕。我们不是手工制作这样的学习目标，而是采用对抗性训练与近似的Gumbel采样器相结合，将生成的分布与人类的分布进行隐式匹配。虽然我们的方法在字幕的正确性方面达到了与现有技术相当的性能，但我们生成了一组不同的字幕，这些字幕明显偏差较小，并且在几个方面更好地匹配统计字。

##### URL
[https://arxiv.org/abs/1703.10476](https://arxiv.org/abs/1703.10476)

##### PDF
[https://arxiv.org/pdf/1703.10476](https://arxiv.org/pdf/1703.10476)

