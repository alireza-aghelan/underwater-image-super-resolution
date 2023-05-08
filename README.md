# underwater-image-super-resolution

In this work, we modify the Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model to enhance the resolution and quality of underwater images. In our proposed approach, the pre-trained generator and discriminator networks of the Real-ESRGAN model are fine-tuned using underwater image datasets. 

We used USR-248 and UFO-120 datasets to fine-tune the Real-ESRGAN model. Our fine-tuned model produces images with better resolution and quality compared to the original model.

Datasets can be downloaded from the link below: 

The download link of the USR-248 dataset:

https://irvlab.cs.umn.edu/resources/usr-248-dataset

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Below are some outputs of the real-esrgan model and the fine-tuned model:

![1](https://user-images.githubusercontent.com/47056654/236956229-a9d68e45-19a2-4f30-8d4c-b7f2c10b54d2.jpeg)
![2](https://user-images.githubusercontent.com/47056654/236956252-27bb3d78-cf22-4b3e-a5b8-0878da7cf721.jpeg)

Magnified regions of underwater images for better comparison between models:

![3](https://user-images.githubusercontent.com/47056654/236956290-49f2b41b-06a7-49c0-baa8-755c3c64def8.jpeg)
![4](https://user-images.githubusercontent.com/47056654/236956309-a892d60e-96c7-44cf-b17f-a5e78f1bc6b9.jpeg)
