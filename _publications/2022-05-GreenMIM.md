---
title: "Green Hierarchical Vision Transformer for Masked Image Modeling"
collection: publications
permalink: /publication/2022-05-GreenMIM
excerpt: 'Efficient masked image modeling with hierarchical vision transformers.'
date: 2022-05-01
venue: 'Thirty-sixth Conference on Neural Information Processing Systems'
paperurl: 'https://arxiv.org/abs/2205.13515'
citation: 'Lang Huang, Shan You, Mingkai Zheng, Fei Wang, Chen Qian, Toshihiko Yamasaki (2022). &quot;Green Hierarchical Vision Transformer for Masked Image Modeling; <i>Thirty-sixth Conference on Neural Information Processing Systems</i>.'
---
*Abstract*: We present an efficient approach for Masked Image Modeling (MIM) with hierarchical Vision Transformers (ViTs), e.g., Swin Transformer, allowing the hierarchical ViTs to discard masked patches and operate only on the visible ones. Our approach consists of two key components. First, for the window attention, we design a Group Window Attention scheme following the Divide-and-Conquer strategy. To mitigate the quadratic complexity of the self-attention w.r.t. the number of patches, group attention encourages a uniform partition that visible patches within each local window of arbitrary size can be grouped with equal size, where masked self-attention is then performed within each group. Second, we further improve the grouping strategy via the Dynamic Programming algorithm to minimize the overall computation cost of the attention on the grouped patches. As a result, MIM now can work on hierarchical ViTs in a green and efficient way. For example, we can train the hierarchical ViTs about 2.7 faster and reduce the GPU memory usage by 70%, while still enjoying competitive performance on ImageNet classification and the superiority on downstream COCO object detection benchmarks.

[\[Paper\]](https://arxiv.org/abs/2205.13515) [\[Code\]](https://github.com/LayneH/GreenMIM)