# underwater-image-super-resolution

In this project, we fine-tune the Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model for underwater image super-resolution. We use USR-248 dataset for fine-tuning model. The proposed model generates more realistic and higher-quality images compared to the original Real-ESRGAN model.

The download link of the USR-248 dataset:

https://irvlab.cs.umn.edu/resources/usr-248-dataset

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Results for different underwater images are shown in the following figures.

![1](https://user-images.githubusercontent.com/47056654/236956229-a9d68e45-19a2-4f30-8d4c-b7f2c10b54d2.jpeg)
![2](https://user-images.githubusercontent.com/47056654/236956252-27bb3d78-cf22-4b3e-a5b8-0878da7cf721.jpeg)

Columns 1–4 are input images, original Real-ESRGAN outputs, fine-tuned Real-ESRGAN outputs, and original images.


Magnified regions of underwater images to further identify differences:

![3](https://user-images.githubusercontent.com/47056654/236956290-49f2b41b-06a7-49c0-baa8-755c3c64def8.jpeg)
![4](https://user-images.githubusercontent.com/47056654/236956309-a892d60e-96c7-44cf-b17f-a5e78f1bc6b9.jpeg)
