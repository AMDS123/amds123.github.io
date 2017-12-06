---
layout: post
title: "Show, Adapt and Tell: Adversarial Training of Cross-domain Image Captioner"
date: 2017-08-14 15:54:32
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Caption
author: Tseng-Hung Chen, Yuan-Hong Liao, Ching-Yao Chuang, Wan-Ting Hsu, Jianlong Fu, Min Sun
---

* content
{:toc}

##### Abstract
Impressive image captioning results are achieved in domains with plenty of training image and sentence pairs (e.g., MSCOCO). However, transferring to a target domain with significant domain shifts but no paired training data (referred to as cross-domain image captioning) remains largely unexplored. We propose a novel adversarial training procedure to leverage unpaired data in the target domain. Two critic networks are introduced to guide the captioner, namely domain critic and multi-modal critic. The domain critic assesses whether the generated sentences are indistinguishable from sentences in the target domain. The multi-modal critic assesses whether an image and its generated sentence are a valid pair. During training, the critics and captioner act as adversaries -- captioner aims to generate indistinguishable sentences, whereas critics aim at distinguishing them. The assessment improves the captioner through policy gradient updates. During inference, we further propose a novel critic-based planning method to select high-quality sentences without additional supervision (e.g., tags). To evaluate, we use MSCOCO as the source domain and four other datasets (CUB-200-2011, Oxford-102, TGIF, and Flickr30k) as the target domains. Our method consistently performs well on all datasets. In particular, on CUB-200-2011, we achieve 21.8% CIDEr-D improvement after adaptation. Utilizing critics during inference further gives another 4.5% boost.

##### Abstract (translated by Google)
在具有大量训练图像和句子对的域（例如，MSCOCO）中实现令人印象深刻的图像字幕结果。然而，转移到具有显着的域转移但没有配对的训练数据（被称为跨域图像字幕）的目标域仍然在很大程度上尚未被探索。我们提出一种新颖的对抗训练程序，以利用目标领域的不成对数据。引入两个评论家网络来引导字幕，即领域评论家和多模式评论家。领域评论者评估生成的句子是否与目标领域的句子无法区分。多模式评论家评估一个图像及其生成的句子是否是一个有效的对。在培训过程中，批评者和字幕人员充当对手 - 字幕的目的是产生难以区分的句子，而批评者的目的在于区分他们。评估通过策略梯度更新改进了字幕。在推理过程中，我们进一步提出了一种新颖的基于批评的计划方法来选择没有额外监督的高质量句子（例如标签）。为了评估，我们使用MSCOCO作为源域以及其他四个数据集（CUB-200-2011，Oxford-102，TGIF和Flickr30k）作为目标域。我们的方法始终在所有数据集上表现良好。特别是在CUB-200-2011上，适应后我们实现了21.8％的CIDEr-D改进。在推断中利用批评者进一步提高了4.5％。

##### URL
[https://arxiv.org/abs/1705.00930](https://arxiv.org/abs/1705.00930)

