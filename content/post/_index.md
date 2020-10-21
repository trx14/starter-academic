---
draft: false
view: 2
title: Mitigating Gender Bias in Captioning Systmes
date: 2020-10-21T01:47:58.864Z
authors:
  - Ruixiang Tang
  - Mengnan Du
  - Yuening Li
  - Zirui Liu
  - Xia Hu
header:
  caption: ""
  image: ""
featured: false
image:
  filename: examples_cropped-1.png
  preview_only: true
---
Image captioning has made substantial progress with huge supporting image collections sourced from the web. However, recent studies have pointed out that captioning datasets, such as COCO, contain gender bias found in web corpora. As a result, learning models could heavily rely on the learned priors and image context for gender identification, leading to incorrect or even offensive errors. To encourage models to learn correct gender features, we reorganize the COCO dataset and present two new splits COCO-GB V1 and V2 datasets where the train and test sets have different gender-context joint distribution. Models relying on contextual cues will suffer from  huge gender prediction errors on the anti-stereotypical test data. Benchmarking experiments reveal that most captioning models learn gender bias, leading to high gender prediction errors, especially for women. To alleviate the unwanted bias, we propose a new Guided Attention Image Captioning model (GAIC) which provides self-guidance on visual attention to encourage the model to capture correct gender visual evidence. Experimental results validate that GAIC can significantly reduce gender prediction errors with a competitive caption quality. Our codes and the designed benchmark datasets are available at https://github.com/CaptionGenderBias2020.