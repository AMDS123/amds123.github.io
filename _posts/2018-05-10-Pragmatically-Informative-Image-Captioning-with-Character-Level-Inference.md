---
layout: post
title: "Pragmatically Informative Image Captioning with Character-Level Inference"
date: 2018-05-10 17:10:15
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Inference
author: Reuben Cohn-Gordon, Noah Goodman, Christopher Potts
mathjax: true
---

* content
{:toc}

##### Abstract
We combine a neural image captioner with a Rational Speech Acts (RSA) model to make a system that is pragmatically informative: its objective is to produce captions that are not merely true but also distinguish their inputs from similar images. Previous attempts to combine RSA with neural image captioning require an inference which normalizes over the entire set of possible utterances. This poses a serious problem of efficiency, previously solved by sampling a small subset of possible utterances. We instead solve this problem by implementing a version of RSA which operates at the level of characters ("a","b","c"...) during the unrolling of the caption. We find that the utterance-level effect of referential captions can be obtained with only character-level decisions. Finally, we introduce an automatic method for testing the performance of pragmatic speaker models, and show that our model outperforms a non-pragmatic baseline as well as a word-level RSA captioner.

##### Abstract (translated by Google)
我们将神经图像捕获器与Rational Speech Acts（RSA）模型结合起来，形成一个实用信息系统：其目标是生成不仅仅是真实的标题，而且还将它们的输入与相似的图像区分开来。以前将RSA与神经图像字幕组合的尝试需要推理，该推理在整个可能的话语集上进行归一化。这带来了严重的效率问题，以前通过对一小部分可能的话语进行抽样来解决。我们通过在展开标题期间实现一个在字符级别（“a”，“b”，“c”......）操作的RSA版本来解决这个问题。我们发现参考字幕的话语级效应只能通过字符级决策来获得。最后，我们介绍了一种测试语用扬声器模型性能的自动方法，并表明我们的模型优于非实用基线以及单词级RSA字幕。

##### URL
[https://arxiv.org/abs/1804.05417](https://arxiv.org/abs/1804.05417)

##### PDF
[https://arxiv.org/pdf/1804.05417](https://arxiv.org/pdf/1804.05417)

