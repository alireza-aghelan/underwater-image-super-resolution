# Underwater Image Super-Resolution using Generative Adversarial Network-based Model

[**Paper (IEEE)**](https://ieeexplore.ieee.org/abstract/document/10326266) | [**Paper (arXiv Preprint)**](https://arxiv.org/abs/2211.03550)

**Alireza Aghelan**, **Modjtaba Rouhani**

## Overview
This repository presents the implementation of our paper, **Underwater Image Super-Resolution using Generative Adversarial Network-based Model**.

In this work, we fine-tune the pre-trained **Real-ESRGAN** model for underwater image super-resolution. The objective is to improve the resolution and visual quality of underwater images while preserving fine structures and producing more realistic textures.

The model is fine-tuned and evaluated on the **USR-248** dataset. Compared with the original Real-ESRGAN baseline, the fine-tuned model produces underwater images with better perceptual quality and more realistic visual details.

The download link of the USR-248 dataset:

https://irvlab.cs.umn.edu/resources/usr-248-dataset

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

 # Results
 
The following figures demonstrate the results for the images in the test folder of the USR-248 dataset.

<br><br>
<img src="./figures/1.jpg" width="600">

Quantitative comparison between IG-CFAT and GAN-based SR methods.
<br><br>

![1](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/059768a3-4bd7-4207-adc5-91cbad941c6e)

Columns 1–4 are input images, Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and original images.

![2](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/c1dea889-1ffc-441c-969b-26caf42295ca)

Magnified regions of underwater images. Columns 1–4 are input images, Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and original images.
