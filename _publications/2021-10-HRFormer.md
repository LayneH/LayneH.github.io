---
title: "HRFormer: High-Resolution Vision Transformer for Dense Prediction"
collection: publications
permalink: /publication/2021-10-HRFormer
excerpt: 'New algorithm for learning from corruted data.'
date: 2021-10-01
venue: 'Thirty-fifth Conference on Neural Information Processing Systems'
paperurl: 'https://arxiv.org/abs/2110.09408'
citation: 'Yuhui Yuan, Rao Fu, Lang Huang, Weihong Lin, Chao Zhang, Xilin Chen, Jingdong Wang (2021). &quot;HRFormer: High-Resolution Vision Transformer for Dense Prediction; <i>Thirty-fifth Conference on Neural Information Processing Systems</i>.'
---

*Abstract*: We present a High-Resolution Transformer (HRFormer) that learns high-resolution representations for dense prediction tasks, in contrast to the original Vision Transformer that produces low-resolution representations and has high memory and computational cost. We take advantage of the multi-resolution parallel design introduced in high-resolution convolutional networks (HRNet), along with local-window self-attention that performs self-attention over small non-overlapping image windows, for improving the memory and computation efficiency. In addition, we introduce a convolution into the FFN to exchange information across the disconnected image windows. We demonstrate the effectiveness of the HighResolution Transformer on both human pose estimation and semantic segmentation tasks, e.g., HRFormer outperforms Swin transformer by 1.3 AP on COCO pose estimation with 50% fewer parameters and 30% fewer FLOPs.

[\[Paper\]](https://arxiv.org/abs/2110.09408) [\[Code\]](https://github.com/HRNet/HRFormer)