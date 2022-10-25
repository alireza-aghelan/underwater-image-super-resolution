# underwater-image-super-resolution

Underwater images are used in oceanic engineering and various applications such as underwater robot vision and underwater autonomous vehicles, etc. Single image super-resolution (SISR) methods can improve the resolution and quality of underwater images. 

Real-Enhanced Super-Resolution Generative Adversarial Network (Real-ESRGAN) is one of the recent practical models that have been used to generate higher-resolution images from lower-resolution input images. 
In this work, we use this model to increase the resolution and quality of underwater images. In our proposed approach, the pre-trained generator and discriminator networks of the real-esrgan model are fine-tuned using underwater image datasets.

We used the USR-248 dataset and UFO-120 dataset to fine-tune the real-esrgan model.
Our fine-tuned model produces images with better resolution and quality compared to the original real-esrgan model.

Datasets can be downloaded from the link below: 

USR-248 Dataset:

https://irvlab.cs.umn.edu/resources/usr-248-dataset

UFO-120 Dataset:

https://irvlab.cs.umn.edu/resources/ufo-120-dataset

All details and fine-tuning parameters are available in the finetune_realesrgan_x4plus.yml file.

It is also possible to test the original real-esrgan model and fine-tuned model in the fine_tune_underwater.ipynb file

Below are some outputs of the real-esrgan model and the fine-tuned model:

1–4 columns are the LR degraded images, the outputs of the original real-esrgan, the outputs of the fine-tuned model after 8 epoch, and the outputs of the fine-tuned model after 20 epoch.

![1](https://user-images.githubusercontent.com/47056654/197768768-e011c4da-7c5a-4317-8e9e-ff72136098e4.jpeg)
![2](https://user-images.githubusercontent.com/47056654/197768822-c6f91077-97bc-4bea-bdd7-6fe8c434b705.jpeg)
![3](https://user-images.githubusercontent.com/47056654/197768869-c94ac521-27ac-4f8a-97e0-939fbf3768cc.jpeg)
![4](https://user-images.githubusercontent.com/47056654/197768901-0a77acb9-9eae-41d5-bb18-b74b5f932162.jpeg)
![5](https://user-images.githubusercontent.com/47056654/197768931-5fe18c9a-86fb-401f-b713-8618912ee32a.jpeg)

Magnified regions of underwater images for better comparison between models:

![6](https://user-images.githubusercontent.com/47056654/197769955-31c7105b-ff68-436c-8ade-e873b130367f.jpeg)
![7](https://user-images.githubusercontent.com/47056654/197769987-5ba814bc-e9cb-41c7-9fba-06f556ac7193.jpeg)
![8](https://user-images.githubusercontent.com/47056654/197770040-69e2fdcb-c54b-414b-8213-e095ea11798a.jpeg)
![9](https://user-images.githubusercontent.com/47056654/197770070-35e5d74b-9890-4daa-8023-aee48063e6d6.jpeg)




