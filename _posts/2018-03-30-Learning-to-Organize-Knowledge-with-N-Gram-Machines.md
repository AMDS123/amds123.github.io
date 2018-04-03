---
layout: post
title: "Learning to Organize Knowledge with N-Gram Machines"
date: 2018-03-30 22:59:15
categories: arXiv_AI
tags: arXiv_AI Knowledge QA GAN Language_Model
author: Fan Yang, Jiazhong Nie, William W. Cohen, Ni Lao
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) had great success on NLP tasks such as language modeling, machine translation and certain question answering (QA) tasks. However, the success is limited at more knowledge intensive tasks such as QA from a big corpus. Existing end-to-end deep QA models (Miller et al., 2016; Weston et al., 2014) need to read the entire text after observing the question, and therefore their complexity in responding a question is linear in the text size. This is prohibitive for practical tasks such as QA from Wikipedia, a novel, or the Web. We propose to solve this scalability issue by using symbolic meaning representations, which can be indexed and retrieved efficiently with complexity that is independent of the text size. More specifically, we use sequence-to-sequence models to encode knowledge symbolically and generate programs to answer questions from the encoded knowledge. We apply our approach, called the N-Gram Machine (NGM), to the bAbI tasks (Weston et al., 2015) and a special version of them ("life-long bAbI") which has stories of up to 10 million sentences. Our experiments show that NGM can successfully solve both of these tasks accurately and efficiently. Unlike fully differentiable memory models, NGM's time complexity and answering quality are not affected by the story length. The whole system of NGM is trained end-to-end with REINFORCE (Williams, 1992). To avoid high variance in gradient estimation, which is typical in discrete latent variable models, we use beam search instead of sampling. To tackle the exponentially large search space, we use a stabilized auto-encoding objective and a structure tweak procedure to iteratively reduce and refine the search space.

##### Abstract (translated by Google)
深度神经网络（DNNs）在NLP任务（例如语言建模，机器翻译和某些问题回答（QA）任务）上取得了巨大成功。然而，在更大的知识密集型任务中，例如来自大语料库的QA，成功是有限的。现有的端到端深度QA模型（Miller et al。，2016; Weston et al。，2014）需要在观察问题后阅读整篇文章，因此它们在回答问题时的复杂程度在文本大小上是线性的。这对于维基百科的QA，小说或网站等实际任务而言是不可接受的。我们建议通过使用符号含义表示来解决这种可伸缩性问题，这些表示可以通过独立于文本大小的复杂性进行索引和检索。更具体地说，我们使用序列 - 序列模型来对符号进行符号化编码，并生成程序来回答编码知识中的问题。我们将这种称为N-Gram Machine（NGM）的方法应用于bAbI任务（Weston et al。，2015）及其特殊版本（“终生bAbI”），故事的故事高达1000万句。我们的实验表明NGM可以准确有效地解决这两项任务。与完全可区分的内存模型不同，NGM的时间复杂度和回答质量不受故事长度的影响。 NGM的整个系统是用REINFORCE进行端对端培训的（Williams，1992）。为了避免梯度估计中的高度变化，这在离散潜变量模型中是典型的，我们使用波束搜索而不是采样。为了解决指数级的大搜索空间，我们使用稳定的自动编码目标和结构调整过程来迭代地减少和优化搜索空间。

##### URL
[http://arxiv.org/abs/1711.06744](http://arxiv.org/abs/1711.06744)

##### PDF
[http://arxiv.org/pdf/1711.06744](http://arxiv.org/pdf/1711.06744)

