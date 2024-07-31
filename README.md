# BNR(Under review) 

## Abstract
In weakly- supervised semantic segmentation (WSSS) using only image-level class labels, a problem with convolutional neural network-based class activation maps is that they tend to activate the most discriminative local regions of objects. Conversely, Transformer-based methods learn global features but suffer from background noise contamination. This study focuses on addressing the issue of background noise in attention weights within existing WSSS based on a Conformer, known as TransCAM. The proposed method successfully reduces background noise, leading to improved accuracy of pseudo-labels. The experimental results demonstrate that our model achieves segmentation performance of 70.5% on the PASCAL VOC 2012 validation data, 71.1% on the test data, and 45.9% on MS COCO 2014 data, outperforming TransCAM in terms of segmentation performance.

<img src="example_bnr.png" width="900">

## Acknowledge 
This implementation is based on [TransCAM](https://github.com/liruiwen/TransCAM). Thanks for the awesome work.
Li, Ruiwen, et al. "Transcam: Transformer attention-based cam refinement for weakly supervised semantic segmentation." Journal of Visual Communication and Image Representation 92 (2023): 103800.




