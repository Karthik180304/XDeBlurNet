# XDeBurNet for Chest Xray Deblurring

Radiography is extensively used in almost all medical specialities, and the quality of the radiographs has a great influence on the diagnostic decisions. Unsharpness is one of the major sources of quality degradation in radiographs. To address this challenge, we propose XDeBlurNet, a novel deep learning (DL) framework for X-ray image deblurring that integrates a cross-shaped window (CSWin) transformer into a U-Net architecture. The model captures the local texture and long-range dependencies using CSWin self-attention and employs Content-Aware ReAssembly of Features (CARAFE) for efficient and high-fidelity upsampling. Furthermore, a composite loss function combining Charbonnier loss, structural similarity index measure (SSIM) loss, and perceptual loss ensures optimized performance across pixel-level accuracy, structural consistency, and perceptual quality.

On a benchmark dataset of synthetically blurred chest X-rays, XDeBlurNet achieved the highest average peak signal-to-noise ratio (PSNR) of 34.45 dB and SSIM of 0.93, outperforming seven state-of-the-art (SOTA) DL-based image deblurring models, including Convolutional neural network (CNN), Fully convolutional network (FCN), Densely connected convolutional network (DenseNet), U-Net, Transformer-based U-Net (TransUNet), Shifted window U-Net (SwinUNet), and Generative adversarial network (GAN). These results indicate XDeBlurNet's superior ability to restore radiographs degraded by unsharpness. 

## Dataset

The model was trained and evaluated on the following dataset:

**Chest Xray Deblurring Dataset**: [Drive Link](https://drive.google.com/drive/folders/1hi5i5t1sPngXcwma9jdB_plbD4TESI7K?usp=sharing)
