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
我们将一个神经图像标题和一个Rational Speech Acts（RSA）模型结合起来，建立一个实用的信息系统：它的目标是生成不仅仅是真实的标题，而且还将它们的输入与类似的图像区分开来。先前将RSA与神经图像字幕组合的尝试需要推理，其对可能话语的整个集合进行归一化。这造成了一个严重的效率问题，以前通过对可能话语的一小部分进行抽样来解决。相反，我们通过实现在展开标题期间操作字符级别（“a”，“b”，“c”...）的RSA版本来解决此问题。我们发现，只有字符级别的决定才能获得指称字幕的话语级效果。最后，我们介绍一种用于测试语用说话人模型性能的自动方法，并且表明我们的模型胜过非实用基线以及字级RSA字幕。

##### URL
[https://arxiv.org/abs/1804.05417](https://arxiv.org/abs/1804.05417)

##### PDF
[https://arxiv.org/pdf/1804.05417](https://arxiv.org/pdf/1804.05417)

