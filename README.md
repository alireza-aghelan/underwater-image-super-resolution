# Underwater image super-resolution

In this project, we fine-tune the pre-trained Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model for underwater image super-resolution. We use USR-248 dataset for fine-tuning the model. The proposed model generates more realistic and higher-quality images compared to the original Real-ESRGAN model.

The download link of the USR-248 dataset:

https://irvlab.cs.umn.edu/resources/usr-248-dataset

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Some results for the images of the USR-248 test folder are demonstrated in the following figures.

![1](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/059768a3-4bd7-4207-adc5-91cbad941c6e)

Columns 1–4 are input images, Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and original images.

![2](https://github.com/alireza-aghelan/underwater-image-super-resolution/assets/47056654/c1dea889-1ffc-441c-969b-26caf42295ca)

Magnified regions of underwater images. Columns 1–4 are input images, Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and original images.
