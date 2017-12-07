---
layout: post
title: "ImageNet Training in Minutes"
date: 2017-12-06 05:03:46
categories: arXiv_CV
tags: arXiv_CV
author: Yang You, Zhao Zhang, Cho-Jui Hsieh, James Demmel, Kurt Keutzer
mathjax: true
---

* content
{:toc}

##### Abstract
Finishing 90-epoch ImageNet-1k training with ResNet-50 on a NVIDIA M40 GPU takes 14 days. This training requires 10^18 single precision operations in total. On the other hand, the world's current fastest supercomputer can finish 2 * 10^17 single precision operations per second (Dongarra et al 2017, https://www.top500.org/lists/2017/06/). If we can make full use of the supercomputer for DNN training, we should be able to finish the 90-epoch ResNet-50 training in one minute. However, the current bottleneck for fast DNN training is in the algorithm level. Specifically, the current batch size (e.g. 512) is too small to make efficient use of many processors. For large-scale DNN training, we focus on using large-batch data-parallelism synchronous SGD without losing accuracy in the fixed epochs. The LARS algorithm (You, Gitman, Ginsburg, 2017, <a href="http://export.arxiv.org/abs/1708.03888">arXiv:1708.03888</a>) enables us to scale the batch size to extremely large case (e.g. 32K). We finish the 100-epoch ImageNet training with AlexNet in 11 minutes on 1024 CPUs. About three times faster than Facebook's result (Goyal et al 2017, <a href="http://export.arxiv.org/abs/1706.02677">arXiv:1706.02677</a>), we finish the 90-epoch ImageNet training with ResNet-50 in 20 minutes on 2048 KNLs without losing accuracy. Furthermore, when we increase the batch size to above 16K, our accuracy is much higher than Facebook's on corresponding batch sizes. Our source code is available upon request.

##### Abstract (translated by Google)
在NVIDIA M40 GPU上使用ResNet-50完成90个纪元的ImageNet-1k训练需要14天的时间。这次培训总共需要10 ^ 18个单精度操作。另一方面，目前世界上最快的超级计算机可以每秒完成2 * 10 ^ 17个单精度操作（Dongarra等2017，https://www.top500.org/lists/2017/06/）。如果我们能够充分利用超级计算机进行DNN训练，我们应该能够在一分钟内完成90分钟的ResNet-50训练。但是，目前DNN训练的瓶颈在算法层面。特别地，当前的批量大小（例如512）太小而不能有效地使用许多处理器。对于大规模DNN培训，我们重点关注在固定时期使用大批量数据并行同步SGD，而不会损失准确性。 LARS算法（You，Gitman，Ginsburg，2017，<a href="http://export.arxiv.org/abs/1708.03888"> arXiv：1708.03888 </a>）使我们能够将批量调整到极大情况下（例如32K）。我们在1024个CPU上用11分钟完成了100分钟的ImageNet培训。大约比Facebook的结果快三倍（Goyal et al 2017，<a href="http://export.arxiv.org/abs/1706.02677"> arXiv：1706.02677 </a>），我们完成了90个纪元的ImageNet培训ResNet-50在2048 KNL上20分钟内不失准确性。此外，当我们将批量增加到16K以上时，我们的准确性远远高于Facebook在相应的批量上的大小。我们的源代码可根据要求提供。

##### URL
[http://arxiv.org/abs/1709.05011](http://arxiv.org/abs/1709.05011)

##### PDF
[http://arxiv.org/pdf/1709.05011](http://arxiv.org/pdf/1709.05011)

