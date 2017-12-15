---
layout: post
title: "Document Decomposition of Bangla Printed Text"
date: 2017-01-27 12:54:52
categories: arXiv_SD
tags: arXiv_SD Recognition
author: Md. Fahad Hasan, Tasmin Afroz, Sabir Ismail, Md. Saiful Islam
mathjax: true
---

* content
{:toc}

##### Abstract
Today all kind of information is getting digitized and along with all this digitization, the huge archive of various kinds of documents is being digitized too. We know that, Optical Character Recognition is the method through which, newspapers and other paper documents convert into digital resources. But, it is a fact that this method works on texts only. As a result, if we try to process any document which contains non-textual zones, then we will get garbage texts as output. That is why; in order to digitize documents properly they should be prepossessed carefully. And while preprocessing, segmenting document in different regions according to the category properly is most important. But, the Optical Character Recognition processes available for Bangla language have no such algorithm that can categorize a newspaper/book page fully. So we worked to decompose a document into its several parts like headlines, sub headlines, columns, images etc. And if the input is skewed and rotated, then the input was also deskewed and de-rotated. To decompose any Bangla document we found out the edges of the input image. Then we find out the horizontal and vertical area of every pixel where it lies in. Later on the input image was cut according to these areas. Then we pick each and every sub image and found out their height-width ratio, line height. Then according to these values the sub images were categorized. To deskew the image we found out the skew angle and de skewed the image according to this angle. To de-rotate the image we used the line height, matra line, pixel ratio of matra line.

##### Abstract (translated by Google)
今天所有的信息都是数字化的，随着这些数字化，各种文件的巨大档案也正在数字化。我们知道，光学字符识别是通过报纸和其他纸质文件转换成数字资源的方法。但是，这种方法只适用于文本。因此，如果我们试图处理任何包含非文本区域的文档，那么我们将得到垃圾文本作为输出。这就是为什么;为了正确数字化文件，他们应该小心翼翼地妥善处理。在进行预处理的同时，根据分类对不同地区的文档进行恰当的分割是最重要的。但是，可用于孟加拉语的光学字符识别过程没有这样的算法，可以将报纸/书页充分分类。所以我们将文档分解成多个部分，如标题，子标题，列，图像等。如果输入是倾斜的和旋转的，那么输入也被去偏斜和去旋转。为了分解任何孟加拉文件，我们找到了输入图像的边缘。然后我们找出它所在的每个像素的水平和垂直区域。之后根据这些区域切割输入图像。然后我们挑选每个子图像，找出它们的高宽比，线高。然后根据这些值对子图像进行分类。为了校正图像，我们找出了倾斜角度，并根据这个角度对图像进行偏斜。为了旋转图像，我们使用了matra线的线高，matra线，像素比。

##### URL
[https://arxiv.org/abs/1701.08706](https://arxiv.org/abs/1701.08706)

##### PDF
[https://arxiv.org/pdf/1701.08706](https://arxiv.org/pdf/1701.08706)

