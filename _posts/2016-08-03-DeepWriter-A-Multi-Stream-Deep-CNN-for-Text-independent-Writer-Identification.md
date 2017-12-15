---
layout: post
title: "DeepWriter: A Multi-Stream Deep CNN for Text-independent Writer Identification"
date: 2016-08-03 03:26:58
categories: arXiv_CV
tags: arXiv_CV Classification
author: Linjie Xing, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Text-independent writer identification is challenging due to the huge variation of written contents and the ambiguous written styles of different writers. This paper proposes DeepWriter, a deep multi-stream CNN to learn deep powerful representation for recognizing writers. DeepWriter takes local handwritten patches as input and is trained with softmax classification loss. The main contributions are: 1) we design and optimize multi-stream structure for writer identification task; 2) we introduce data augmentation learning to enhance the performance of DeepWriter; 3) we introduce a patch scanning strategy to handle text image with different lengths. In addition, we find that different languages such as English and Chinese may share common features for writer identification, and joint training can yield better performance. Experimental results on IAM and HWDB datasets show that our models achieve high identification accuracy: 99.01% on 301 writers and 97.03% on 657 writers with one English sentence input, 93.85% on 300 writers with one Chinese character input, which outperform previous methods with a large margin. Moreover, our models obtain accuracy of 98.01% on 301 writers with only 4 English alphabets as input.

##### Abstract (translated by Google)
由于书面内容的巨大变化以及不同作者的写作风格的模糊，独立于文本的作者身份识别具有挑战性。本文提出DeepWriter，一个深度的多流CNN学习认识作家的深刻的强大代表。 DeepWriter将本地手写补丁作为输入，并用softmax分类丢失进行训练。主要贡献有：1）设计和优化作者身份识别任务的多流结构; 2）我们引入数据增强学习来提高DeepWriter的性能; 3）我们引入了一个补丁扫描策略来处理不同长度的文本图像。另外，我们发现英文和中文等不同的语言可能具有共同的作者识别特征，而联合训练可以产生更好的表现。在IAM和HWDB数据集上的实验结果表明，我们的模型具有很高的识别准确率：301名作者为99.01％，657名作者为97.03％，一个英文句子输入，300名作者为93.85％，一个汉字输入，比以前的方法大幅度上涨。此外，我们的模型在301名作者中获得98.01％的准确性，只有4个英文字母作为输入。

##### URL
[https://arxiv.org/abs/1606.06472](https://arxiv.org/abs/1606.06472)

##### PDF
[https://arxiv.org/pdf/1606.06472](https://arxiv.org/pdf/1606.06472)

