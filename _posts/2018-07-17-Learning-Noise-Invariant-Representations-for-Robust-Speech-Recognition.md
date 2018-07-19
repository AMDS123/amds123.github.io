---
layout: post
title: "Learning Noise-Invariant Representations for Robust Speech Recognition"
date: 2018-07-17 18:15:14
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Davis Liang, Zhiheng Huang, Zachary C. Lipton
mathjax: true
---

* content
{:toc}

##### Abstract
Despite rapid advances in speech recognition, current models remain brittle to superficial perturbations to their inputs. Small amounts of noise can destroy the performance of an otherwise state-of-the-art model. To harden models against background noise, practitioners often perform data augmentation, adding artificially-noised examples to the training set, carrying over the original label. In this paper, we hypothesize that a clean example and its superficially perturbed counterparts shouldn't merely map to the same class --- they should map to the same representation. We propose invariant-representation-learning (IRL): At each training iteration, for each training example,we sample a noisy counterpart. We then apply a penalty term to coerce matched representations at each layer (above some chosen layer). Our key results, demonstrated on the Librispeech dataset are the following: (i) IRL significantly reduces character error rates (CER) on both 'clean' (3.3% vs 6.5%) and 'other' (11.0% vs 18.1%) test sets; (ii) on several out-of-domain noise settings (different from those seen during training), IRL's benefits are even more pronounced. Careful ablations confirm that our results are not simply due to shrinking activations at the chosen layers.

##### Abstract (translated by Google)
尽管在语音识别方面取得了快速进展，但目前的模型仍然很脆弱，无法对其输入进行表面干扰。少量噪音可能会破坏其他最先进模型的性能。为了使模型不受背景噪声的影响，从业者经常进行数据增加，在训练集中添加人工噪声示例，并带有原始标签。在本文中，我们假设一个干净的例子及其表面上不相干的对应物不应该只映射到同一个类 - 它们应该映射到相同的表示。我们提出了不变表示学习（IRL）：在每次训练迭代中，对于每个训练示例，我们对一个嘈杂的对应物进行采样。然后，我们应用惩罚项来强制每层（在某些选定层之上）的匹配表示。我们在Librispeech数据集上展示的关键结果如下：（i）IRL显着降低了“干净”（3.3％对6.5％）和“其他”（11.0％对18.1％）测试集的字符错误率（CER） ; （ii）在几个域外噪声设置（与培训期间看到的不同）中，IRL的好处更加明显。仔细消融证实我们的结果不仅仅是由于所选层的激活减少。

##### URL
[https://arxiv.org/abs/1807.06610](https://arxiv.org/abs/1807.06610)

##### PDF
[https://arxiv.org/pdf/1807.06610](https://arxiv.org/pdf/1807.06610)

