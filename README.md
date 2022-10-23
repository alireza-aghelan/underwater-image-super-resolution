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

![1](https://user-images.githubusercontent.com/47056654/197418252-b98f0fd3-0d5d-4513-811c-dd98237ae396.jpeg)
![2](https://user-images.githubusercontent.com/47056654/197418296-0fcbb5ce-adf2-4d32-b01c-28088b539da3.jpeg)
![3](https://user-images.githubusercontent.com/47056654/197418550-ab2ccd0a-fb62-4304-a706-e9cb530294fb.jpeg)
![4](https://user-images.githubusercontent.com/47056654/197418571-56779d22-253f-429b-98e4-665c85fcaa1e.jpeg)
![5](https://user-images.githubusercontent.com/47056654/197418695-030469b3-0836-47c3-bd38-25aa2796951b.jpeg)

Magnified regions of underwater images for better comparison between models:





