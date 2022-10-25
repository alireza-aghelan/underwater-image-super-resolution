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

![6](https://user-images.githubusercontent.com/47056654/197768966-18323072-2b91-44ec-99bd-84bbc1d0b061.jpeg)
![7](https://user-images.githubusercontent.com/47056654/197768989-3f3b1292-f0f3-4f38-a237-640acd9aed5b.jpeg)
![8](https://user-images.githubusercontent.com/47056654/197769016-c5a70c42-9631-4fd5-8597-8129b96fc372.jpeg)
![9](https://user-images.githubusercontent.com/47056654/197769044-2edb1c40-56bc-43f9-a992-b5f0728e024a.jpeg)




