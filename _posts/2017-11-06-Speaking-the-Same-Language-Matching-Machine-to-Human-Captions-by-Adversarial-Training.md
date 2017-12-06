---
layout: post
title: 'Speaking the Same Language: Matching Machine to Human Captions by Adversarial Training'
date: 2017-11-06 15:43:47
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Caption
author: Rakshith Shetty, Marcus Rohrbach, Lisa Anne Hendricks, Mario Fritz, Bernt Schiele
---

* content
{:toc}

##### Abstract
While strong progress has been made in image captioning over the last years, machine and human captions are still quite distinct. A closer look reveals that this is due to the deficiencies in the generated word distribution, vocabulary size, and strong bias in the generators towards frequent captions. Furthermore, humans -- rightfully so -- generate multiple, diverse captions, due to the inherent ambiguity in the captioning task which is not considered in today's systems. To address these challenges, we change the training objective of the caption generator from reproducing groundtruth captions to generating a set of captions that is indistinguishable from human generated captions. Instead of handcrafting such a learning target, we employ adversarial training in combination with an approximate Gumbel sampler to implicitly match the generated distribution to the human one. While our method achieves comparable performance to the state-of-the-art in terms of the correctness of the captions, we generate a set of diverse captions, that are significantly less biased and match the word statistics better in several aspects.

##### Abstract (translated by Google)
机器人字幕虽然在过去几年已经取得了很大的进步，但机器和人物的字幕仍然很明显。仔细观察发现，这是由于生成的词分布，词汇量大小和生成者对频繁标题的强烈偏见所导致的。此外，由于字幕任务中固有的模糊性，在当今系统中没有考虑到，人类 - 理所当然地 - 生成多种多样的字幕。为了应对这些挑战，我们将字幕生成器的训练目标从再现地面字幕改为生成一组与人类生成的字幕无法区分的字幕。我们不是手工制作这样一个学习目标，而是采用对抗训练和一个近似的Gumbel采样器来隐含地匹配产生的分布到人的分布。虽然我们的方法在字幕的正确性方面达到了与现有技术水平相当的性能，但是我们生成了一系列不同的字幕，这些字幕的偏差明显较小，并在多个方面更好地匹配字数统计。

##### URL
[https://arxiv.org/abs/1703.10476](https://arxiv.org/abs/1703.10476)

