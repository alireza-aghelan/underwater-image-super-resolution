# underwater-image-super-resolution

In this work, we modify the Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) model to enhance the resolution and quality of underwater images. In our proposed approach, the pre-trained generator and discriminator networks of the Real-ESRGAN model are fine-tuned using underwater image datasets. 

We used USR-248 and UFO-120 datasets to fine-tune the Real-ESRGAN model. Our fine-tuned model produces images with better resolution and quality compared to the original model.

Datasets can be downloaded from the link below: 

The download link of the USR-248 dataset:

https://irvlab.cs.umn.edu/resources/usr-248-dataset

The Real-ESRGAN code is borrowed from https://github.com/xinntao/Real-ESRGAN.

Below are some outputs of the real-esrgan model and the fine-tuned model:

![1](https://user-images.githubusercontent.com/47056654/236952666-04c06073-9b52-4dad-8cfc-ebefedbc8514.jpeg)
![2](https://user-images.githubusercontent.com/47056654/236952703-ee82aaac-367c-4523-b8e9-69c3bdc6bcd2.jpeg)

Magnified regions of underwater images for better comparison between models:

![3](https://user-images.githubusercontent.com/47056654/236955690-0a897613-6b83-42e2-8fcd-efe13d48afd8.jpeg)
![4](https://user-images.githubusercontent.com/47056654/236955703-e2b3a367-e5df-4212-a548-656c3355a910.jpeg)
