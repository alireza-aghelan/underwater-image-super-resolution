# Underwater Image Super-Resolution using Generative Adversarial Network-based Model

[**IEEE Paper**](https://ieeexplore.ieee.org/abstract/document/10326266) | [**arXiv Preprint**](https://arxiv.org/abs/2211.03550)

**Alireza Aghelan**, **Modjtaba Rouhani**

## Overview
This repository provides the implementation of our paper, **Underwater Image Super-Resolution using Generative Adversarial Network-based Model**.

In this paper, we fine-tune **Real-ESRGAN** for underwater image super-resolution. The objective is to improve the resolution and visual quality of underwater images while preserving fine details and producing realistic textures. The model is fine-tuned on the **USR-248** dataset. In comparison with the original Real-ESRGAN baseline, our model generates underwater images with improved perceptual quality and more realistic details.

The **USR-248** dataset can be accessed [here](https://irvlab.cs.umn.edu/resources/usr-248-dataset).

This work is built upon [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN).

 # Results
 
The following figures demonstrate the results for the images in the test folder of the USR-248 dataset.

---

![1](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/059768a3-4bd7-4207-adc5-91cbad941c6e)

Columns 1–4 are input images, Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and original images.

---

![2](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/c1dea889-1ffc-441c-969b-26caf42295ca)

Magnified regions of underwater images. Columns 1–4 are input images, Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and original images.
