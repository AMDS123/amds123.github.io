---
layout: post
title: "Recurrent Scene Parsing with Perspective Understanding in the Loop"
date: 2017-12-06 00:05:17
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction Recognition
author: Shu Kong, Charless Fowlkes
mathjax: true
---

* content
{:toc}

##### Abstract
Objects may appear at arbitrary scales in perspective images of a scene, posing a challenge for recognition systems that process images at a fixed resolution. We propose a depth-aware gating module that adaptively selects the pooling field size in a convolutional network architecture according to the object scale (inversely proportional to the depth) so that small details are preserved for distant objects while larger receptive fields are used for those nearby. The depth gating signal is provided by stereo disparity or estimated directly from monocular input. We integrate this depth-aware gating into a recurrent convolutional neural network to perform semantic segmentation. Our recurrent module iteratively refines the segmentation results, leveraging the depth and semantic predictions from the previous iterations. 
 Through extensive experiments on four popular large-scale RGB-D datasets, we demonstrate this approach achieves competitive semantic segmentation performance with a model which is substantially more compact. We carry out extensive analysis of this architecture including variants that operate on monocular RGB but use depth as side-information during training, unsupervised gating as a generic attentional mechanism, and multi-resolution gating. We find that gated pooling for joint semantic segmentation and depth yields state-of-the-art results for quantitative monocular depth estimation.

##### Abstract (translated by Google)
对象可以以任意比例出现在场景的透视图像中，对以固定分辨率处理图像的识别系统构成挑战。我们提出了一个深度感知的门控模块，根据对象尺度（与深度成反比），在卷积网络体系结构中自适应地选择池场大小，以便为远处的对象保留小的细节，而对于附近的那些则使用较大的接受场。深度门控信号由立体视差提供或直接从单眼输入估算。我们将这种深度感知门控整合到经常性的卷积神经网络中来执行语义分割。我们经常使用的模块迭代地改进分割结果，利用以前迭代的深度和语义预测。
 通过对四种流行的大规模RGB-D数据集进行广泛的实验，我们证明了这种方法通过一个更紧凑的模型实现了竞争性的语义分割性能。我们对这种体系结构进行了广泛的分析，包括在单眼RGB上操作的变体，但是在训练期间使用深度作为边信息，无监督门控作为通用注意机制，以及多分辨率门控。我们发现用于联合语义分割和深度的门控池可以为定量单眼深度估计提供最新的结果。

##### URL
[http://arxiv.org/abs/1705.07238](http://arxiv.org/abs/1705.07238)

##### PDF
[http://arxiv.org/pdf/1705.07238](http://arxiv.org/pdf/1705.07238)

