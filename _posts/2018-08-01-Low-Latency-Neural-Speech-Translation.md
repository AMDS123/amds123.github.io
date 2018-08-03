---
layout: post
title: "Low-Latency Neural Speech Translation"
date: 2018-08-01 18:17:05
categories: arXiv_CL
tags: arXiv_CL NMT Deep_Learning
author: Jan Niehues, Ngoc-Quan Pham, Thanh-Le Ha, Matthias Sperber, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
Through the development of neural machine translation, the quality of machine translation systems has been improved significantly. By exploiting advancements in deep learning, systems are now able to better approximate the complex mapping from source sentences to target sentences. But with this ability, new challenges also arise. An example is the translation of partial sentences in low-latency speech translation. Since the model has only seen complete sentences in training, it will always try to generate a complete sentence, though the input may only be a partial sentence. We show that NMT systems can be adapted to scenarios where no task-specific training data is available. Furthermore, this is possible without losing performance on the original training data. We achieve this by creating artificial data and by using multi-task learning. After adaptation, we are able to reduce the number of corrections displayed during incremental output construction by 45%, without a decrease in translation quality.

##### Abstract (translated by Google)
通过神经机器翻译的发展，机器翻译系统的质量得到了显着提高。通过利用深度学习的进步，系统现在能够更好地逼近从源句到目标句的复杂映射。但凭借这种能力，也出现了新的挑战。一个例子是低延迟语音翻译中部分句子的翻译。由于模型在训练中只看到完整的句子，所以它总是会尝试生成一个完整的句子，尽管输入可能只是一个部分句子。我们表明，NMT系统可以适应没有任务特定训练数据的情况。此外，这可以在不损失原始训练数据的性能的情况下实现。我们通过创建人工数据和使用多任务学习来实现这一目标。经过调整后，我们能够将增量输出结构中显示的校正次数减少45％，而不会降低翻译质量。

##### URL
[http://arxiv.org/abs/1808.00491](http://arxiv.org/abs/1808.00491)

##### PDF
[http://arxiv.org/pdf/1808.00491](http://arxiv.org/pdf/1808.00491)

