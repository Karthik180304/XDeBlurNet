# CSWin-UNet for Medical Image Deblurring

CSWin-UNet, a novel deep learning architecture for medical image deblurring that combines CSWin Transformer blocks with U-Net architecture.

## Overview

CSWin-UNet incorporates a stripe-based self-attention mechanism that efficiently captures both local details and global context, making it particularly effective for medical image deblurring tasks. The architecture features:

- CSWin Transformer blocks with horizontal and vertical stripe attention
- Multi-scale feature extraction through a hierarchical encoder-decoder structure
- Adaptive stripe width for balancing computational efficiency and attention effectiveness
- CARAFE upsampling technique for high-quality feature map reconstruction
- Skip connections to preserve spatial information across different resolution scales

## Dataset

The model was trained and evaluated on the following dataset:

**Medical Image Deblurring Dataset**: [https://drive.google.com/drive/folders/1hi5i5t1sPngXcwma9jdB_plbD4TESI7K?usp=sharing](https://drive.google.com/drive/folders/1hi5i5t1sPngXcwma9jdB_plbD4TESI7K?usp=sharing)
