---
layout: post
title: "Google's Multilingual Neural Machine Translation System: Enabling Zero-Shot Translation"
date: 2017-08-21 20:33:43
categories: arXiv_CL
tags: arXiv_CL Attention Transfer_Learning NMT
author: Melvin Johnson, Mike Schuster, Quoc V. Le, Maxim Krikun, Yonghui Wu, Zhifeng Chen, Nikhil Thorat, Fernanda Viégas, Martin Wattenberg, Greg Corrado, Macduff Hughes, Jeffrey Dean
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a simple solution to use a single Neural Machine Translation (NMT) model to translate between multiple languages. Our solution requires no change in the model architecture from our base system but instead introduces an artificial token at the beginning of the input sentence to specify the required target language. The rest of the model, which includes encoder, decoder and attention, remains unchanged and is shared across all languages. Using a shared wordpiece vocabulary, our approach enables Multilingual NMT using a single model without any increase in parameters, which is significantly simpler than previous proposals for Multilingual NMT. Our method often improves the translation quality of all involved language pairs, even while keeping the total number of model parameters constant. On the WMT'14 benchmarks, a single multilingual model achieves comparable performance for English$\rightarrow$French and surpasses state-of-the-art results for English$\rightarrow$German. Similarly, a single multilingual model surpasses state-of-the-art results for French$\rightarrow$English and German$\rightarrow$English on WMT'14 and WMT'15 benchmarks respectively. On production corpora, multilingual models of up to twelve language pairs allow for better translation of many individual pairs. In addition to improving the translation quality of language pairs that the model was trained with, our models can also learn to perform implicit bridging between language pairs never seen explicitly during training, showing that transfer learning and zero-shot translation is possible for neural translation. Finally, we show analyses that hints at a universal interlingua representation in our models and show some interesting examples when mixing languages.

##### Abstract (translated by Google)
我们提出一个简单的解决方案，使用单个神经机器翻译（NMT）模型来翻译多种语言。我们的解决方案不需要改变我们的基础系统的模型架构，而是在输入句子的开头引入一个人工标记来指定所需的目标语言。包括编码器，解码器和注意力的模型的其余部分保持不变，并在所有语言中共享。使用共享的文字词汇，我们的方法使用单一模型启用多语言NMT，而不增加任何参数，这比以前的多语种NMT提议要简单得多。我们的方法经常提高所有相关语言对的翻译质量，即使在保持模型参数总数不变的情况下。在WMT'14的基准测试中，单一的多语言模型在英语$ \ rightarrow $ French方面获得了可比的性能，并且超过了英语$ \ rightarrow $德语的最新结果。同样，单一的多语言模型也分别超过了法语$ \ rightarrow $英语和德语$ \ rightarrow $英语在WMT'14和WMT'15基准测试中的最新结果。在生产语料库上，多达十二种语言对的多语言模型可以更好地翻译许多单独的对。除了提高模型训练的语言对的翻译质量之外，我们的模型还可以学习在训练期间从未明确看到的语言对之间进行隐式桥接，表明转移学习和零点翻译可能用于神经翻译。最后，我们展示分析，暗示在我们的模型中的通用国际语言表示，并显示混合语言时的一些有趣的例子。

##### URL
[https://arxiv.org/abs/1611.04558](https://arxiv.org/abs/1611.04558)

##### PDF
[https://arxiv.org/pdf/1611.04558](https://arxiv.org/pdf/1611.04558)

