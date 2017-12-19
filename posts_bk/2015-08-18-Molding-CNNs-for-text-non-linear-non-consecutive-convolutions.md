---
layout: post
title: "Molding CNNs for text: non-linear, non-consecutive convolutions"
date: 2015-08-18 02:52:40
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification Classification Deep_Learning
author: Tao Lei, Regina Barzilay, Tommi Jaakkola
mathjax: true
---

* content
{:toc}

##### Abstract
The success of deep learning often derives from well-chosen operational building blocks. In this work, we revise the temporal convolution operation in CNNs to better adapt it to text processing. Instead of concatenating word representations, we appeal to tensor algebra and use low-rank n-gram tensors to directly exploit interactions between words already at the convolution stage. Moreover, we extend the n-gram convolution to non-consecutive words to recognize patterns with intervening words. Through a combination of low-rank tensors, and pattern weighting, we can efficiently evaluate the resulting convolution operation via dynamic programming. We test the resulting architecture on standard sentiment classification and news categorization tasks. Our model achieves state-of-the-art performance both in terms of accuracy and training speed. For instance, we obtain 51.2% accuracy on the fine-grained sentiment classification task.

##### Abstract (translated by Google)
深度学习的成功往往源于精心挑选的运营构件。在这项工作中，我们修改了CNN中的时间卷积操作，以更好地适应文本处理。我们不用拼接词表达，而是使用张量代数，并使用低秩n-gram张量来直接利用卷积阶段已经存在的词之间的相互作用。此外，我们将n-gram卷积扩展为非连续词，以识别具有插入词的模式。通过低秩张量和模式加权的组合，我们可以通过动态编程高效地评估所得到的卷积运算。我们在标准情感分类和新闻分类任务上测试最终的体系结构。我们的模型在准确性和训练速度方面达到了最先进的性能。例如，细粒度情感分类任务的准确率为51.2％。

##### URL
[https://arxiv.org/abs/1508.04112](https://arxiv.org/abs/1508.04112)

##### PDF
[https://arxiv.org/pdf/1508.04112](https://arxiv.org/pdf/1508.04112)

