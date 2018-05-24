---
layout: post
title: "Distribution Matching Losses Can Hallucinate Features in Medical Image Translation"
date: 2018-05-22 20:06:33
categories: arXiv_CV
tags: arXiv_CV GAN
author: Joseph Paul Cohen, Margaux Luck, Sina Honari
mathjax: true
---

* content
{:toc}

##### Abstract
This paper discusses how distribution matching losses, such as those used in CycleGAN, when used to synthesize medical images can lead to mis-diagnosis of medical conditions. It seems appealing to use these new image synthesis methods for translating images from a source to a target domain because they can produce high quality images and some even do not require paired data. However, the basis of how these image translation models work is through matching the translation output to the distribution of the target domain. This can cause an issue when the data provided in the target domain has an over or under representation of some classes (e.g. healthy or sick). When the output of an algorithm is a transformed image there are uncertainties whether all known and unknown class labels have been preserved or changed. Therefore, we recommend that these translated images should not be used for direct interpretation (e.g. by doctors) because they may lead to misdiagnosis of patients based on hallucinated image features by an algorithm that matches a distribution. However there are many recent papers that seem as though this is the goal.

##### Abstract (translated by Google)
本文讨论分配匹配损失（如CycleGAN中使用的分配匹配损失）在用于合成医学图像时如何导致对医疗条件的错误诊断。使用这些新的图像合成方法将图像从源代码转换为目标域名似乎很有吸引力，因为它们可以生成高质量的图像，有些甚至不需要配对数据。然而，这些图像翻译模型如何工作的基础是通过将翻译输出与目标域的分布进行匹配。当目标域中提供的数据具有某些类的过度或不足表示时（例如健康或生病），这可能会导致问题。当算法的输出是变换图像时，是否存在所有已知和未知的类别标签已被保存或改变的不确定性。因此，我们建议这些翻译后的图像不应该用于直接解释（例如由医生），因为它们可能导致基于幻觉图像特征的患者通过与分布匹配的算法误诊。然而，最近有许多报道似乎认为这是目标。

##### URL
[http://arxiv.org/abs/1805.08841](http://arxiv.org/abs/1805.08841)

##### PDF
[http://arxiv.org/pdf/1805.08841](http://arxiv.org/pdf/1805.08841)

