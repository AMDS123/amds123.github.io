---
layout: post
title: "Guided Open Vocabulary Image Captioning with Constrained Beam Search"
date: 2017-07-19 22:01:27
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Embedding Prediction
author: Peter Anderson, Basura Fernando, Mark Johnson, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
Existing image captioning models do not generalize well to out-of-domain images containing novel scenes or objects. This limitation severely hinders the use of these models in real world applications dealing with images in the wild. We address this problem using a flexible approach that enables existing deep captioning architectures to take advantage of image taggers at test time, without re-training. Our method uses constrained beam search to force the inclusion of selected tag words in the output, and fixed, pretrained word embeddings to facilitate vocabulary expansion to previously unseen tag words. Using this approach we achieve state of the art results for out-of-domain captioning on MSCOCO (and improved results for in-domain captioning). Perhaps surprisingly, our results significantly outperform approaches that incorporate the same tag predictions into the learning algorithm. We also show that we can significantly improve the quality of generated ImageNet captions by leveraging ground-truth labels.

##### Abstract (translated by Google)
现有的图像字幕模型不能很好地概括为包含新颖场景或对象的域外图像。这种限制严重阻碍了这些模型在处理野外图像的现实世界应用中的使用。我们使用灵活的方法解决了这个问题，使现有的深字幕体系结构能够在测试时利用图像标记器，而无需重新训练。我们的方法使用约束光束搜索来强制在输出中包含所选标记词，以及固定的，预训练的词嵌入以便于词汇扩展到先前看不见的标记词。使用这种方法，我们可以获得MSCOCO上域外字幕的最新结果（以及域内字幕的改进结果）。也许令人惊讶的是，我们的结果明显优于将相同标签预测纳入学习算法的方法。我们还表明，通过利用地面实况标签，我们可以显着提高生成的ImageNet字幕的质量。

##### URL
[https://arxiv.org/abs/1612.00576](https://arxiv.org/abs/1612.00576)

##### PDF
[https://arxiv.org/pdf/1612.00576](https://arxiv.org/pdf/1612.00576)

